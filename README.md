# Git_KervAutomation
Kerv Digital Automation

This framework is created using Cucumber TestNG. 

Under Config folder---->Configuration.properties file has the browser, chrome path, URL & wait. we can change these parameters.

This framework is dynamic and can take any JoRole and Candidate Details.

Steps to make changes to Job Role Or Candidate Details:
1. Goto SRC-->test--->resources--->Features---Kfeature.feature file
2. Change the Job Role, County or Candidate Details. 

Steps to Execute the framework:
1. Goto command Prompt--->create directory where program file is kept
2. Run command mvn test

Or
1. Select KERVJOB project--->right click--->Run as---->Maven Test


Report:
1. HTMLReport is under test-output---->extent---->ExtentHtml.html
2. Spart---Index.html

Logs:
Logs are under---target--->logs-->app.log






