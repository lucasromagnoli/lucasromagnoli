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
                            .addKnowledge(Knowledges.LANGUAGE, Language.JAVA)
                            .addKnowledge((Knowledges.LANGUAGE, Language.JAVASCRIPT)
                            .addKnowledge(Knowledges.LANGUAGE, Language.CPP)
                            .addKnowledge(Knowledges.LANGUAGE, Language.LUA)
                            .addKnowledge(Knowledges.LANGUAGE, Language.CSHARP)
                            .addKnowledge(Knowledges.JAVA, Java.SPRING_FRAMEWORK)
                            .addKnowledge(Knowledges.JAVASCRIPT, Javascript.NODEJS)
                            .addKnowledge(Knowledges.DATABASE, Database.ORACLE)
                            .addKnowledge(Knowledges.DATABASE, Database.MYSQL)
                            .addKnowledge(Knowledges.DATABASE, Database.POSTGRESQL)
                            .addKnowledge(Knowledges.DATABASE, Database.MONGO)
                            .addKnowledge(Knowledges.DATABASE, Database.REDIS)
                            .addKnowledge(Knowledges.MISC, Misc.DOCKER)
                            .addKnowledge(Knowledges.MISC, Misc.JENKINS)
                            .addKnowledge(Knowledges.MISC, Misc.GIT)
                        .build()
    }
}
````
