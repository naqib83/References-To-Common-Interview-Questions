# References-To-Common-Interview-Questions

#### 1. How to make singleton beans thread safe in spring framework?

we can change spring bean scope to request, prototype or session to achieve thread-safety at the cost of performance. It’s a design decision and based on the project requirements.

#### 2. How to deploy microservice / spring boot application?

***Embedded Server:*** A Spring Boot application can be deployed with an embedded server. You can generate a JAR file and run it like any other JAR file.

***Standalone Server:*** You can also deploy a Spring Boot application in a standalone server (e.g., standalone Tomcat). For this, you can generate a WAR file for your Spring Boot application (instead of a JAR) and deploy it like a normal WAR file.

