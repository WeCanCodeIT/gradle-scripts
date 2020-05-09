# Gradle build scripts

1. Open your Git Bash terminal (or bash on *other* OSes).
1. Create a folder for your project (suggested location is within the `code` folder).
1. Change directory (`cd`) into your project folder.
1. Copy/paste the following `curl` command to retrieve a `build.gradle` file that includes core unit-testing dependencies. Don't worry about its contents now, we'll go into those later:

	`curl https://raw.githubusercontent.com/WeCanCodeIT/gradle-scripts/master/junit5-test-dependencies/build.gradle --output build.gradle`

1. Open IntelliJ and select `Open` from the `File` menu or the 'Welcom to IntelliJ IDEA' window.  Navigate to the folder that you created in the Git Bash terminal, select the build.gradle file, click `OK`, and select open as project.
1. In the `Project` window right click on the project folder at the top and select `New`-> `Directory`, and select `src/main/java` from the 'Gradle Source Sets.  Do the same for `src/test/java`.
