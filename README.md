# openshift-diy-jar
Openshift config to run a Spring Boot JAR

- Create a DIY application in Openshift.
- Remove this dummy yourSpringBootApp.jar and put your Spring Boot generated .jar file in the root of this repository.
- Then push (or force push) this repository to your remote Openshift application.

The push should trigger the application start (with Java 8) and you are done! ;)