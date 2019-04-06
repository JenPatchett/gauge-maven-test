# gauge-maven-test
A gauge, maven, java test framework using [scala-webapp](https://github.com/rayhaanbhikha/scala-webapp) by Rayhaan Bhikha. 

To run this project, first clone it to your computer, then skip to **Clone Scala-webapp** section to continue setup. Or read on to set up your own test framework from scratch.


## To Create Your Own Maven Project (IntelliJ)
Follow this 5 min [YouTube tutorial](https://www.youtube.com/watch?v=fi7ZbL23I2E) or read on for instructions.


File > New > Project

Maven > Project SDK *(choose version)* 

Click Next

GroupId: `com.sky`

ArtifactId *(your project name)*: `gauge-maven-test`

Click Next 

Project Name: `gauge-maven-test`

Project Location: *(where you want to save it)*

Click Finish

Click ‘Enable Auto Import’ *(on Maven popup that appears)*

Click View *(from top menu)* > Tool Windows > Maven


## Initialise Gauge

**From IntelliJ Terminal:**

Initialise as Gauge Java project: `gauge init java`

*Before continuing, resolve any dependencies in /src/test/java/StepImplementation.java*

Clean and compile the project: `mvn clean compile`

Run the example specs (tests) file: `gauge run specs`

To view test results open html report located in: /reports/html-report/index.html


## Clone Scala-webapp
Clone [scala-webapp](https://github.com/rayhaanbhikha/scala-webapp) from Rayhaan Bhikha

Once cloned, run Docker, cd into scala-webapp in Terminal, then follow instructions in the [README.md](https://github.com/rayhaanbhikha/scala-webapp)


## Docker
After following all instructions in the [README.md](https://github.com/rayhaanbhikha/scala-webapp) for scala-webapp, verify both Docker containers are now running: 

`docker ps` - should see *userdatastore* and *usergateway*

To stop all currently running containters: `docker stop $(docker ps -q)`

To restart the containers: `docker start userdatastore usergateway`

To stop these containers: `docker stop userdatastore usergateway`

To verify these containers are no longer running: `docker ps`


