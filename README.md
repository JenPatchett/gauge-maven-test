# gauge-maven-test
A gauge, maven, java test framework

## Create Maven Project (IntelliJ)
5 min video tutorial here: https://www.youtube.com/watch?v=fi7ZbL23I2E 


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

Clean and compile the project: `mvn clean compile`

Run the example specs (tests) file: `gauge run specs`

To view test results open html report located in: /reports/html-report/index.html



