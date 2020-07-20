````java
package github;

/**
 * @author github.com/lucasromagnoli
 * @since 20/07/2020
 */
public class GitHub {
    public void readme() {
        Person person = new Person();
        person.setName("Lucas Ramos Romagnoli");
        person.setDescription("I am a professional who love to code. " +
                              "Always looking for the best programming solutions and practices.");
        person.setCity(new City("Goiânia", "Goiás", "Brazil"));
        person.setEmail("lucasr.romagnoli@gmail.com");
        person.getSocialMedias().put(SocialMedia.LINKEDIN, "in/lucasromagnoli");
        person.getKnowledges().put(Knowledges.LANGUAGE, Language.JAVA);
        person.getKnowledges().put(Knowledges.LANGUAGE, Language.JAVASCRIPT);
        person.getKnowledges().put(Knowledges.LANGUAGE, Language.CPP);
        person.getKnowledges().put(Knowledges.LANGUAGE, Language.LUA);
        person.getKnowledges().put(Knowledges.LANGUAGE, Language.CSHARP);
        person.getKnowledges().put(Knowledges.JAVA, Java.SPRING_FRAMEWORK);
        person.getKnowledges().put(Knowledges.JAVASCRIPT, Javascript.NODEJS);
        person.getKnowledges().put(Knowledges.DATABASE, Database.ORACLE);
        person.getKnowledges().put(Knowledges.DATABASE, Database.MYSQL);
        person.getKnowledges().put(Knowledges.DATABASE, Database.POSTGRESQL);
        person.getKnowledges().put(Knowledges.DATABASE, Database.MONGO);
        person.getKnowledges().put(Knowledges.DATABASE, Database.REDIS);
        person.getKnowledges().put(Knowledges.MISC, Misc.DOCKER);
        person.getKnowledges().put(Knowledges.MISC, Misc.JENKINS);
        person.getKnowledges().put(Knowledges.MISC, Misc.GIT);
    }
}
````
