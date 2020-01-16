# Gradle build scripts

## For students using Eclipse and JUnit 4: setting up a new project

1. Open your Git Bash terminal (or bash on *other* OSes).
1. Create a folder for your project (suggested location is within the `code` folder).
1. Change directory (`cd`) into your project folder.
1. Copy/paste the following `curl` command to retrieve a `build.gradle` file that includes core unit-testing dependencies. Don't worry about its contents now, we'll go into those later:

	`curl https://raw.githubusercontent.com/WeCanCodeIT/gradle-scripts/master/core-java-test-dependencies/build.gradle --output build.gradle`
		
1. Run `gradle eclipse` to set up your Eclipse project. These scripts contain a custom task that will automagically create your standard source folders, `src/main/java` (for production code) and `src/test/java` (for tests).
1. Import the project into your workspace (`File->Import…->General/Existing Projects into Workspace`)

## For students using IntelliJ and JUnit 5: setting up a new project

1. Open your Git Bash terminal (or bash on *other* OSes).
1. Create a folder for your project (suggested location is within the `code` folder).
1. Change directory (`cd`) into your project folder.
1. Copy/paste the following `curl` command to retrieve a `build.gradle` file that includes core unit-testing dependencies. Don't worry about its contents now, we'll go into those later:

	`curl https://raw.githubusercontent.com/WeCanCodeIT/gradle-scripts/master/junit5-test-dependencies/build.gradle --output build.gradle`

1. Open IntelliJ and select `Open` from the `File` menu or the 'Welcom to IntelliJ IDEA' window.  Navigate to the folder that you created in the Git Bash terminal, select the build.gradle file, click `OK`, and select open as project.
1. In the `Project` window right click on the project folder at the top and select `New`-> `Directory`, and select `src/main/java` from the 'Gradle Source Sets.  Do the same for `src/test/java`.

## For instructors:

Pulling a build for a project with a simple `src` (and optionally `test`) folder:

`curl https://raw.githubusercontent.com/WeCanCodeIT/gradle-scripts/master/simple-src-folder/build.gradle --output build.gradle`