```java
import java.util.List;
import java.util.Map;

public class Oluni {

    public static class ContactInfo {
        private final String telegram = "@oluni_official";
        private final String email = "oluniofficial@gmail.com";

        public String getTelegram() {
            return telegram;
        }

        public String getEmail() {
            return email;
        }
    }

    public static class Life {
        private final List<String> languages = List.of("Russian", "English", "Ukrainian");

        public List<String> getLanguages() {
            return languages;
        }

        public int getAge() {
            return age;
        }
    }

    public static class Coding {
        private final Map<String, List<String>> languages = Map.of(
                "coding", List.of("Python", "Java"),
                "learning", List.of("HTML", "CSS")
        );

        public Map<String, List<String>> getLanguages() {
            return languages;
        }
    }


    private final ContactInfo contact = new ContactInfo();
    private final Life life = new Life();
    private final Coding coding = new Coding();


    public ContactInfo getContact() {
        return contact;
    }

    public Life getLife() {
        return life;
    }

    public Coding getCoding() {
        return coding;
    }
}
```
