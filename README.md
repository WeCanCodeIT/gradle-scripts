# Gradle build scripts

## For students: setting up a new project

1. Open your Git Bash terminal (or bash on *other* OSes).
1. Create a folder for your project (suggested location is within the `code` folder).
1. Change directory (`cd`) into your project folder.
1. Copy/paste the following `curl` command to retrieve a `build.gradle` file that includes core unit-testing dependencies. Don't worry about its contents now, we'll go into those later:

	`curl https://raw.githubusercontent.com/WeCanCodeIT/gradle-scripts/master/core-java-test-dependencies/build.gradle --output build.gradle`
		
1. Run `gradle eclipse` to set up your Eclipse project. These scripts contain a custom task that will automagically create your standard source folders, `src/main/java` (for production code) and `src/test/java` (for tests).
1. Import the project into your workspace (`File->Import…->General/Existing Projects into Workspace`)

## For instructors:

Pulling a build for a project with a simple `src` (and optionally `test`) folder:

`curl https://raw.githubusercontent.com/WeCanCodeIT/gradle-scripts/master/simple-src-folder/build.gradle --output build.gradle`