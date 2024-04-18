# chatsecretary-server
Java/Kotlin server for ChatSecretary

## Requirements
- JDK 21
- OpenAI API Key
- Run this in your shell
```
export SPRING_AI_OPENAI_API_KEY=<INSERT KEY HERE>
```

## How to contribute:
- Make your changes in a new branch
- Run the `build` Gradle task within your IDE, then the `bootRun` task to test your changes. Alternatively, you can run the following in the root directory using cli:
```
./gradlew build && ./gradlew bootRun
```
- Make a PR against main and ask for a review
- Once review is completed and approved, you can rebase and merge