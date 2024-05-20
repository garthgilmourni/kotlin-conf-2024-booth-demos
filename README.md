# Kotlin Conf 2024

## Standalone projects for exploring JetBrains tools and libraries
 
The following projects are included in this repository: 

1. **ai-assistant-ktor** - A simple Task Manager web application. Used to demo the AI Assistant with Ktor.
2. **ai-assistant-photography** - A function for calculating the [Exposure Value](https://en.wikipedia.org/wiki/Exposure_value) from photography. Used to demo the AI Assistant.
3. **ai-assistant-regex** - A function that emulates the UNIX grep command. Used to demo the AI Assistant.
4. **kmp-weather-app-start** - The starter project for an exercise in building cross platform mobile and desktop applications with [Kotlin Multiplatform](https://kotlinlang.org/docs/multiplatform.html) and [Compose Multiplatform](https://www.jetbrains.com/lp/compose-multiplatform/).
5. **kmp-weather-app-finish** - The solution to the above exercise.
6. **ktor-graphql-integration** - Using the GraphQL plugin for Ktor, as an alternative to REST.
7. **ktor-kmp-retries** - Support for retrying requests in Ktor.
8. **ktor-koin-integration** -  Using the Koin DI framework within a Ktor service.
9. **ktor-native** - Building a Ktor service using the Kotlin Native compiler.
10. **ktor-testing** - Writing Unit and Integration tests for Ktor services.
11. **ktor-tutorial-exposed** -  A project to accompany the Ktor tutorial on using the [Exposed SQL library](https://github.com/JetBrains/Exposed) within Ktor services.
12. **ktor-tutorial-full-stack** -  A project to accompany the Ktor tutorial on building full stack applications via [the Kotlin Multiplatform Wizard](https://kmp.jetbrains.com/).
13. **ktor-tutorial-rest** -  A project to accompany the Ktor tutorial on REST.
14. **ktor-tutorial-routing** -  A project to accompany the Ktor requests and routing tutorial.
15. **ktor-tutorial-server-pages** -  A project to accompany the Ktor tutorial on Thymeleaf templates.
16. **ktor-tutorial-websockets** -  A project to accompany the Ktor WebSockets tutorial.
17. **ktor-websockets** -  Support for WebSockets in Ktor.
18. **notebook-dataframes** - A project to accompany the [introductory DataFrame tutorial](https://blog.jetbrains.com/kotlin/2024/04/a-step-by-step-guide-to-performing-data-analysis-with-kotlin-dataframe/).
19. **notebook-ktor-integration** - An example of using the Kotlin Notebook extensions to the Ktor Http Client.

All projects are standalone, so open the project folder that interests you in the IDE. If you open the repo directly it will probably take a very long time to load all the dependencies.

The idea is to use these projects as starting points for exploring the [Ktor](https://ktor.io/), [Dataframe](https://github.com/Kotlin/dataframe), and [Compose Multiplatform](https://www.jetbrains.com/lp/compose-multiplatform/) libraries. Plus of course the [IntelliJ IDEA IDE](https://www.jetbrains.com/idea/), [Fleet](https://www.jetbrains.com/fleet/) code editor, [AI Assistant](https://www.jetbrains.com/ai/), and [Notebook](https://plugins.jetbrains.com/plugin/16340-kotlin-notebook) plugin.

Much more comprehensive samples for the above can be found here:

* [Sample applications for Ktor](https://github.com/ktorio/ktor-samples)
* [Sample applications for Compose Multiplatform](https://github.com/JetBrains/compose-multiplatform/blob/master/examples/README.md)
* [Cross platform projects created with KMP](https://www.jetbrains.com/help/kotlin-multiplatform-dev/multiplatform-samples.html)

Note you can create your own projects (ourside the IDE) via the following wizards:

* The [Ktor Project Generator](https://start.ktor.io/#/settings)
* The [Kotlin Multiplafform Wizard](https://kmp.jetbrains.com/)