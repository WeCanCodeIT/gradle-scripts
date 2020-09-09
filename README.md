# Gradle Build Scripts

Instructions on how to build a basic Gradle project with JUnit 5, AssertJ, Hamcrest and Mockito libraries.

## What is Gradle?
Are you are familiar with the concept of home meal delivery services?  Not ordering delivery from your favorite pizza place, but _Blue Apron_ or _Hello Fresh_.  These services don't cook a meal for you, but give you the ingredients you need to prepare the meal yourself, they might even include a recipe card to help you out with directions.  You can think of Gradle as one of these services, but for Java!  We use a `build.gradle` file to tell Gradle what libraries (think ingredients) for our project and Gradle will go to a central repository and fetch those libraries for us.  We then have access to those libraries in the project we are working on.  Gradle is a *build tool*, a common phrase for an application that helps developers setup development projects and manage the complexities of a larger project with external libraries.

## Instructions

### Basic Java Project with JUnit 5:
1. Open your Git Bash terminal (or bash on *other* OSes).
1. Create a folder for your project using `mkdir <new directory name>`.
1. Change directory (`cd`) into your project folder.
1. Copy and paste the following into the terminal and hit enter:
  
    `gradle init --type java-application --test-framework junit-jupiter`

1. Select the default options.
1. Open IntelliJ and select `Open` from the `File` menu or the 'Welcome to IntelliJ IDEA' window.  Navigate to the folder that you created in the Git Bash terminal, select the folder, click `OK`.

### Basic Java Project with JUnit 5, AssertJ, Mockito, and Hamcrest:
1. Open your Git Bash terminal (or bash on *other* OSes).
1. Create a folder for your project (suggested location is within the `code` folder).
1. Change directory (`cd`) into your project folder.
1. Copy and paste the following into the terminal and hit enter: 
    
	`gradle init --type java-application --test-framework junit-jupiter`

1. Select the default options.
1. Copy/paste the following `curl` command to retrieve a `build.gradle` file that includes core unit-testing dependencies. Don't worry about its contents now, we'll go into those later:

	`curl https://raw.githubusercontent.com/WeCanCodeIT/gradle-scripts/master/junit5-testing-dependencies/build.gradle --output build.gradle`

1. Open IntelliJ and select `Open` from the `File` menu or the 'Welcome to IntelliJ IDEA' window.  Navigate to the folder that you created in the Git Bash terminal, select the folder, click `OK`.

