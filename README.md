# auth
The auth project creates a wrapper layer for authentication against different providers. For e.g. oAuth, Ldap, ...

### Prerequisites
 - JDK 1.8
 - Maven 3.x
 - MySQL installed
   - Create database : authdb
   - Add db user : admin (Password : admin)
 - Tomcat 8.0
 
### Build Steps
 - #### Build ( from auth directory )
   - ##### Option 1 (Complete build)
     - mvn clean install
   - ##### Option 2 (Skip test : Use this in case there is build failure while running smoke test )
     - mvn clean install -DskipTests
 - #### Copy the server.war generated in the server target directory to your tomcat webapps directory and start tomcat

### Artifacts
 - #### REST API Documentation @ http://localhost:8080/server/api/index.html
 - #### API access @ http://localhost:8080/server/...






 
 
 
 
 
 
 
 
 
 
 

