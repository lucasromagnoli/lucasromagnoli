# Setting up default containers

## Portainer
````sh
sudo docker run -d -p 9000:9000 --name portainer --restart always -v /var/run/docker.sock:/var/run/docker.sock -v ~/workstation/docker/volumes/portainer/data:/data portainer/portainer:alpine
````
## Postgres
````sh
sudo docker run --name postgres_db -e POSTGRES_PASSWORD=postgres -p 5432:5432 -v ~/workstation/docker/volumes/postgres/volumes:/var/lib/postgresql/data -d postgres:11.8-alpine
````
## PgAdmin
````sh
sudo docker run --name pgadmin -p 15432:80 -e "PGADMIN_DEFAULT_EMAIL=lucasr.romagnoli@gmail.com" -e "PGADMIN_DEFAULT_PASSWORD=postgres" -d dpage/pgadmin4
````