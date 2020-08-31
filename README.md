# Angular_SpringBoot_SimpleProject
This is a simple project which uses Angular for the front end and spring boot for the backend to provide services

This is a full stack java web application which implements product management services

Prerequisites to run the project

Java, IntelliJ/Eclipse, Angular 7, maven, npm, nodejs

Steps to run the project

Checkout the git repositoty and import the project into intellij or eclipse as maven project

Now cd to the root of the project and run the below command mvn clean install -DskipTests

Once the build is complete, run the java application using

java -jar target/.jar

Make sure that its running successfully. Now the backend is ready to serve the contents to the frontend

Navigate to the "frontend" directory and install the necessary packages for the angular application using

npm install

Now start the frontend application using

npm start

If there are no errors then navigate to the page http://localhost:4200
