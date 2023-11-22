# CRUD Application with Spring Boot 
This repository contains a simple CRUD (Create, Read, Update, Delete) application developed using Spring Boot. 
The application manages user information, allowing users to be created, updated, and deleted.

## Technologies Used 
* `Java`: Programming language used for backend development.
* `Spring Boot`: Framework for building Java-based enterprise applications.
* `Spring Data JPA`: Part of the Spring Data project, simplifying data access with JPA.
* `Thymeleaf`: Server-side Java template engine for web and standalone environments.
* `HTML`: Markup language for creating user interfaces.
  
## Project Structure
### Controller
* **UserController:** Handles HTTP requests, interacts with the service layer, and manages user-related operations.

### Model
* **User:** Represents the entity with attributes such as id, first name, and last name.
  
### Repository
* **UserRepository:** Interface extending JpaRepository for CRUD operations on the User entity.
  
### Service
* **UserService:** Implements business logic, interacts with the repository, and provides user-related services.

### Application
* **CrudApplication:** Main class with the main method to run the Spring Boot application.
  
## How to Run
* **Clone the repository:** https://github.com/DrDmlg/spring-boot-crud.git
* Open the project in your preferred Java IDE.
* Run the CrudApplication class as a Java application.
* Access the application by navigating to http://localhost:8080/users in your web browser. 

## User Interface
* `Create User`: Access the create user form by clicking on "Create user" on the main page. Fill in the required details and submit the form.
* `View Users`: See the list of existing users on the main page.
* `Update User`: Click on "Edit" next to a user to access the update form. Modify the details and submit the form to update the user.
* `Delete User`: Click on "Delete" next to a user to delete that user from the system.
Feel free to explore and enhance the application based on your requirements. If you have any questions or suggestions, please contact the project maintainer.

## Contact
If you have any questions or suggestions, feel free to reach out to me at *dorokhov.did@gmail.com* or through my GitHub page.
