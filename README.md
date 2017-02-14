# Gradle build scripts

## For students

If you want to pull a build.gradle, open your Git Bash terminal and navigate to your project/repository directory. From there, run one of the the following curl commands to download the appropriate build.gradle. Afterwards, run `gradle eclipse` to set up your Eclipse project, then import it into your workspace. These build files include a task to create default source folders (`src/main/java` and `src/test/java`), so you won't need to do that manually.

### Basic Java project with JUnit test dependency

```
curl https://raw.githubusercontent.com/WeCanCodeIT/gradle-scripts/master/basic-junit/build.gradle --output build.gradle
```

### Java project with JUnit, Mockito, and Hamcrest test dependencies
```
curl https://raw.githubusercontent.com/WeCanCodeIT/gradle-scripts/master/junit-with-mockito-and-hamcrest/build.gradle --output build.gradle
```
