# RepTracker
Our vision is to create **RepTracker**, a smart and simple workout logging app designed for lifters who want to track sets, reps, and progress without the clutter.

## 🚀 Try it out!

**Use RepTracker here:**  
[https://unified-logic-development-team.github.io/RepTracker/](https://unified-logic-development-team.github.io/RepTracker/)

## Requirements

- **Java 21 or newer**
- **Maven 3.9+**

## **Developer Notes:**  
This project is deployed via SpringBoot (https://spring.io/projects/spring-boot), Vaadin (https://vaadin.com/) and fly.io (https://fly.io/). To contribute to the project, follow these steps.
 1. Fork and clone a copy to your local system.
 2. Edit or Add Java code as needed.
 3. Navigate to the top of the repo directory and run the following commands:

**Ubuntu**

```
     sudo apt install maven 
```
```
     mvn spring-boot:run
```

**MacOS**
```
     brew install maven 
```
```
     mvn spring-boot:run
```

**Windows Powershell**

Download chocolatey package manager at https://chocolatey.org/install
```
     choco install maven 
```
```
     mvn spring-boot:run
```

For all other operating systems, refer to https://maven.apache.org/download.cgi and https://maven.apache.org/install.html or your OS package manager.
     
 4. This will run SpringBoot and the application will be available for testing on localhost
 5. Once SpringBoot is running, test out the application: http://localhost:8080/

##
Side Note: If port 8080 is busy, kill the process and run the mvn command again.

To kill the process using a Linux CLI:
```
sudo lsof -t -i:8080
```
```
sudo kill -9 <PID>
```
Then you can successfully run the mvn command
```
mvn spring-boot:run
```
## Automatic Deployment

The application will automatically update as changes are made to the repository.

## Authors

**Unified Logical Development Team**

- Andrew  
- Erik
- Davon  
- Matt  
- Ted  
- Ahmed
