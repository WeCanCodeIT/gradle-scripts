# Gradle build scripts

## For students: setting up a new project

1. Open your Git Bash terminal (or bash on *other* OSes).
1. Create a folder for your project (suggested location is within the `code` folder).
1. Change directory (`cd`) into your project folder.
1. Copy/paste one of these `curl` commands to retrieve a `build.gradle` file:
	- Java project with JUnit test dependency:

		`curl https://raw.githubusercontent.com/WeCanCodeIT/gradle-scripts/master/basic-junit/build.gradle --output build.gradle`

	- Java project with JUnit, Mockito, and Hamcrest test dependencies:

		`curl https://raw.githubusercontent.com/WeCanCodeIT/gradle-scripts/master/junit-with-mockito-and-hamcrest/build.gradle --output build.gradle`
		
1. Run `gradle eclipse` to set up your Eclipse project. These scripts contain a custom task that will automagically create your standard source folders, `src/main/java` (for production code) and `src/test/java` (for tests).
1. Import the project into your workspace (`File->Import…->General/Existing Projects into Workspace`)

## For instructors:

Pulling a build for a project with a simple `src` (and optionally `test`) folder:

	`curl https://raw.githubusercontent.com/WeCanCodeIT/gradle-scripts/master/simple-src-folder/build.gradle --output build.gradle`
