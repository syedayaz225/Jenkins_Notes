# Jenkins_Notes

What is Jenkins
- Jenkins is a CI CD tool
- Free & Open Source
- Written in Java

What is CI & CD
Continuous Integration, Delivery & Deployment

Installation

System Requirements
Memory 256 MB of RAM
Disk Space Depends on your projects
OS Windows, Mac, Ubuntu, Linux
Java 8 or 11 (JDK or JRE)

Installation on Windows
Step 1 : check Java is installed 
Step 2 : Download Jenkins.war file
Step 3 : Goto cmd prompt and run command
   java -jar jenkins.war --httpPort=9191
Step 4 : On browser goto http://localhost:9191
Step 5 : Provide admin password and complete the setup

Installation on Mac

Homebrew

Installation on Linux
https://youtu.be/jmm8DsosBqw

Jenkins Configuration
 
How to change Home Directory
Step 1: Check your Jenkins Home ＞ Manage Jenkins ＞ Configure System
Step 2 : Create a new folder
Step 3 : Copy the data from old folder to new folder
Step 4 : Create/Update env variable JENKINS_HOME
Step 5 : Restart Jenkins

jenkins.xml

JENKINS_HOME

How to setup Git on Jenkins
Step 1 : Goto Manage Jenkins ＞ Manage Plugins
Step 2 : Check if git is already installed in Installed tab
Step 3 : Else goto Available tab and search for git
Step 4 : Install Git
Step 5 : Check git option is present in Job Configuration

Create the first Job on Jenkins
How to connect to Git Remote Repository in Jenkins (GitHub)
Step 1 : Get the url of the remote repository
Step 2 : Add the git credentials on Jenkins
Step 3 : In the jobs configuration goto SCM and provide git repo url in git section
Step 4 : Add the credentials
Step 5 : Run job and check if the repository is cloned

How to use Command Line in Jenkins CLI
Faster, easier, integrate
Step 1 : start Jenkins
Step 2 : goto Manage Jenkins - Configure Global Security - enable security
Step 3 : goto - http://localhost:8080/cli/
Step 4 : download jerkins-cli jar. Place at any location.
Step 5 : test the jenkins command line is working

java -jar jenkins-cli.jar -s http://localhost:8080 /help --username ＜userName＞ --password ＜password＞

How to create Users + Manage + Assign Roles
How to create New Users
How to configure users
How to create new roles
How to assign users to roles
How to Control user access on projects

Step 1 : Create new users
Step 2 : Configure users
Step 3 : Create and manage user roles Role Based Authorization Strategy Plugin - download - restart jenkins
Step 4 : Manage Jenkins - Configure Global Security - Authorization - Role Based Strategy
Step 5 : Create Roles and Assign roles to users
Step 6 : Validate authorization and authentication are working properly

Chain Jobs

Jenkins Pipeline Beginner Tutorial 
How to create Jenkinsfile
- What is pipeline
- What is jenkins pipeline
- What is jenkinsfile
- How to create jenkinsfile

Build ＞ Deploy ＞ Test ＞ Release
Jenkinsfile : Pipeline as a code

Step 1 : Start Jenkins
Step 2 : Install Pipeline Plugin
Step 3 : Create a new job
Step 4 : Create or get Jenkinsfile in Pipeline section
Step 5 : Run and check the output

Jenkins Pipeline 
How to get jenkinsfile from Git SCM

Step 1 : Create a new job or use existing job (type : Pipeline)
Step 2 : Create a repository or GitHub
Step 3 : Add Jenkinsfile in the repo
Step 4 : Under Jenkins job ＞ Pipeline section ＞ Select Definition Pipeline script from SCM
Step 5 : Add repo and jenkinsfile location in the job under Pipeline section
Step 6 : Save & Run

Jenkins Pipeline
How to clone a git repo using Jenkinsfile

all videos on Jenkins
Jenkins is free and the most widely used CI CD tool today
Learning Jenkins
watch again and just to any topic using TimeLine in Description

https://www.youtube.com/watch?v=woMAXn4e8NA&list=LL&index=18&t=94s&ab_channel=AutomationStepbyStep-RaghavPal
Never Stop Learning
Raghav Pal
