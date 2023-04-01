# Java-Application-Injection-Attacks
Java and Spring applications and injection attacks on these applications

Here are the steps followed to create these applications
Prereq - Java version 20, Maven, Docker, IntelliJ, Burpsuite
## Step 1: Parent pom
- Added a local java-maven project named 'java injection demo' and added pom.xml with parent and plugin
- Ran mvn install

## Step 2: Web login module
- Right clicked the above project in IntelliJ and added a module 'web-login'
- Add parent pom(create in step 1) in pom.xml
- Added dependencies
- Add a folder 'src/main/resources/templates/'
- Add 6 thymeleaf files
- Add service classes, apis and spring security controllers
