# lab029-maven-app
### Author: Frank Effrim-Botchey
### This lab creates a simple java app and stores the code on Github.  When the code is updated, the app is automatically built and tested.  If it builds successfully, it is then executed.

# Part 1 Objectives: 
[01] Create a Maven project for a Java app
[02] Store the Maven project in Github
[03] Create a Jenkins project to:
    [3.1] Trigger a Jenkins run when a change is detected on the project's Github repo.
    [3.2] Build & Test the Java app
    [3.3] Execute the Java app only if the Build & Test was successful
[04] Test Part 1 objectives

Note: Steps 3.2 to 3.3 should be configured manually within Jenkins UI
    
# Part 2 Objectives: 
[05] Create a Jenkinsfile to Clean, Test & Package the Maven app.
[06] Store this Jenkins file with the project code in Github.
[07] Configure Jenkins to use the Jenkinsfile instead of the manually configured settings in the Jenkins UI.
[08] Configure Jenkins to send email notification once jenkins run is complete
[09] Test Part 2 objectives

# Part 3 Objectives: 
[10] Create a new Jenkins project using Multipipeline option
[11] Configure this Jenkins project to detect any modification to branches on the Github repo created in part 1.
[12] Create a new Github branch on the project.
[13] Test Part 3 objectives