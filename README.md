# Hi, I'm Jaen

_Computer Systems Engineering Student at [Instituto Tecnológico de Acapulco](https://acapulco.tecnm.mx)_ 💻

_Future developer of mobile applications with [Kotlin](https://kotlinlang.org) and [Swift](https://swift.org)_ 🔬/

[![GitHub Jaen](https://img.shields.io/github/followers/jaennova?label=follow&style=social)](https://github.com/jaennova)

### <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> A little more about me  

```kotlin
val jaen = Developer(
    name = "Jaen",
    languages = listOf("Kotlin", "Java", "Python"),
    codeEditors = listOf(
        "Intellij IDEA", 
        "Visual Studio Code",
        "Android Studio", 
        "Neovim"
    ),
    tools = mapOf(
        "MySQL" to "Databases",
        "Notion" to "Productivity",
        "Figma" to "Design",
        "Jira" to "Project Management"
    ),
    currentFocus = "Exploring new technologies and learning every day",
    challenge = "Turning unfinished ideas into impactful solutions"
)

class Developer(
    val name: String,
    val languages: List<String>,
    val codeEditors: List<String>,
    val tools: Map<String, String>,
    val currentFocus: String,
    val challenge: String
)
fun main() {
    println("Welcome to ${jaen.name}'s GitHub profile!")
    println("🚀 Currently focusing on: ${jaen.currentFocus}")
    println("💻 Proficient in languages: ${jaen.languages.joinToString()}")
    println("🛠️ Preferred code editors: ${jaen.codeEditors.joinToString()}")
    println("🔧 Favorite Tools:")
    jaen.tools.forEach { (tool, category) ->
        println("   - $tool (Category: $category)")
    }
    println("🎯 Biggest Challenge: ${jaen.challenge}")
    println("🌐 Connect with me on GitHub and let's innovate together!")
}
```

