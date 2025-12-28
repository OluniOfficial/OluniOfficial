```kotlin
class Oluni {
    val contact = ContactInfo()
    val life = Life()
    val coding = Coding()

    class ContactInfo {
        val telegram = "@oluni_official"
        val email = "oluniofficial@gmail.com"
    }

    class Life {
        val languages = listOf("Russian", "English", "Ukrainian")
    }

    class Coding {
        val languages = mapOf(
            "coding" to listOf("Java", "Kotlin", "Lua") 
        )
    }

}
```
