# RepTracker

Our vision is to create **RepTracker**, a smart and simple workout logging app designed for lifters who want to track sets, reps, and progress without the clutter.

## 🚀 Try it out!

👉 **Use RepTracker here:**  
[https://unified-logic-development-team.github.io/RepTracker/](https://unified-logic-development-team.github.io/RepTracker/)

## 🏋️

👉 **Developer Notes:**  
This project is deployed via SpringBoot (https://spring.io/projects/spring-boot), Vaadin (https://vaadin.com/) and fly.io (https://fly.io/). To contribute to the project, follow these steps.
 1. Fork and/or Clone a copy to your local system.
 2. Edit or Add java code as needed.
 3. Navigate to where the files are saved locally, and run the following commands:
 
     sudo apt install maven (for Ubuntu)
     
     mvn spring-boot:run
     
 4. This will run SpringBoot and the application will be available for testing on localhost
 5. Once SpringBoot is running, test out the application: http://localhost:8080/

Side Note: If port 8080 is busy, kill the process and run the mvn command again.

To kill the process using a Linux CLI:
sudo lsof -t -i:8080 (This will return PID)
sudo kill -9 <PID>

Then run mvn spring-boot:run again.

The application will automatically update as changes are made to the repository.

##

