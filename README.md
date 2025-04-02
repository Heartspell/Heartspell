<h1 align="center">👨‍💻 Amirhan Ordobaev</h1>
<p align="center">
  <b>C# Developer | Learning Kotlin | Competitive Programmer | Researcher</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%23-%2368217A?style=for-the-badge&logo=c-sharp&logoColor=white">
  <img src="https://img.shields.io/badge/Kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white">
  <img src="https://img.shields.io/badge/ICPC-%230092CC.svg?style=for-the-badge&logo=codeforces&logoColor=white">
  <img src="https://img.shields.io/badge/Codeforces-%231E90FF.svg?style=for-the-badge&logo=codeforces&logoColor=white">
</p>

```Kotlin
data class DeveloperProfile(
    val name: String,
    val pronouns: List<String>,
    val code: List<String>,
    val askMeAbout: List<String>,
    val technologies: Technologies,
    val architecture: List<String>,
    val currentFocus: String
)

data class Technologies(
    val backEnd: Map<String, List<String>>,
    val databases: List<String>
)

val amirhan = DeveloperProfile(
    name = "Amirhan",
    pronouns = listOf("he", "him"),
    code = listOf("C#", "Kotlin"),
    askMeAbout = listOf("competitive programming", "problem-solving", "researching"),
    technologies = Technologies(
        backEnd = mapOf(
            "C#" to listOf("ASP.Net Core", "Entity Framework"),
            "Kotlin" to listOf("Firebase")
        ),
        databases = listOf("SQL Server")
    ),
    architecture = listOf("Event-driven architecture", "Microservices", "Domain-driven design"),
    currentFocus = "Learning Kotlin"
)
```
