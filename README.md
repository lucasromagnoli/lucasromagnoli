````java
package github;

/**
 * @author github.com/lucasromagnoli
 * @since 20/07/2020
 */
public class GitHub {
    public void readme() {
        Person person = PersonBuilder
                            .name("Lucas Ramos Romagnoli")
                            .description("I am a professional who love to code. " +
                                         "Always looking for the best programming solutions and practices.")
                            .email("lucasr.romagnoli@gmail.com")
                            .addSocialMedia(SocialMedia.LINKEDIN, "in/lucasromagnoli")
                            .addCertificate(Company.ORACLE, Java.OCAJP)
                            .addKnowledge(Knowledges.LANGUAGE, Language.JAVA)
                            .addKnowledge(Knowledges.JAVA, Java.SPRING_FRAMEWORK)
                            .addKnowledge(Knowledges.LANGUAGE, Language.JAVASCRIPT)
                            .addKnowledge(Knowledges.JAVASCRIPT, Javascript.NODEJS)
                            .addKnowledge(Knowledges.LANGUAGE, Language.CPP)
                            .addKnowledge(Knowledges.LANGUAGE, Language.LUA)
                            .addKnowledge(Knowledges.LANGUAGE, Language.CSHARP)
                            .addKnowledge(Knowledges.DATABASE, Database.ORACLE)
                            .addKnowledge(Knowledges.DATABASE, Database.MYSQL)
                            .addKnowledge(Knowledges.DATABASE, Database.POSTGRESQL)
                            .addKnowledge(Knowledges.DATABASE, Database.MONGO)
                            .addKnowledge(Knowledges.DATABASE, Database.REDIS)
                            .addKnowledge(Knowledges.DEVOPS, Misc.DOCKER)
                            .addKnowledge(Knowledges.DEVOPS, Misc.JENKINS)
                            .addKnowledge(Knowledges.DEVOPS, Misc.GIT)
                        .build()
    }
}
````
