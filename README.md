#task1
Task 1 involved creating a Spring Boot application with the following components:

1. Spring Boot Application Setup
   - Created a new Spring Boot project using Spring Initializr
   - Project name: fist-project-spring
   - Dependencies: Spring Web, Thymeleaf

2. Controller Implementation
   - Created GreetingController class
   - Implemented GET mapping for "/greeting" endpoint
   - Added request parameter handling for "name" with default value "World"
   - Used Model to pass data to view

3. View Template
   - Created greeting.html using Thymeleaf
   - Added welcome message for Vistula University
   - Included Vistula logo image
   - Implemented dynamic name display using Thymeleaf syntax

4. Application Properties
   - Configured application name in application.properties

The application successfully displays a greeting page with:
- A welcome message for Vistula University
- The Vistula logo
- A personalized greeting that uses the name parameter from the URL

## Screenshots

![Page Screenshot 1](Screenshot%202025-05-19%20at%204.12.25%E2%80%AFPM.png)

![Page Screenshot 2](Screenshot%202025-05-19%20at%204.12.33%E2%80%AFPM.png)

![Page Screenshot 3](Screenshot%202025-05-19%20at%204.15.58%E2%80%AFPM.png)




