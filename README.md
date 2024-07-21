````java
package github;

/**
 * @author github.com/lucasromagnoli
 * @since 2009
 */
public class GitHub {
    public void readme() {
        Person me = PersonBuilder
                .name("Lucas Romagnoli")
                .currentContext("Developing with AWS Cloud Resources, Java, Spring Framework and Docker.",
                        "Always looking for distributed, scalable and fault tolerant solution.")
                .email("lucasr.romagnoli@gmail.com")
                .socialMedia(SocialMedia.LINKEDIN, "in/lucasromagnoli")
                .certificate(Company.AWS, AWS.DEVELOPER)
                .certificate(Company.AWS, AWS.ARCHITECT)
                .certificate(Company.ORACLE, Java.OCAJP)
                .build();
    }
}
````
