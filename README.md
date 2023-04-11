# Angular-SpringBoot_CRUD_App
CRUD App using UI: Angular, Node js and in Backend: Maven-Spring boot, Hibernate, mysql, tomcat.

## Steps to follow
1. Install node.js
2. Install Angular-CLI
```bash
  npm install -g @angular/cli
```
3. Install Maven: If you don't have Maven installed on your machine, download and install it from the official website.
4. Install MySQL
5. Create Database in MySQL workbench:
```bash
  create database crudappdb;
```
6. Configure database credentials: Open the src/main/resources/application.properties file of the Spring Boot project and configure the database credentials. Update the following properties according to your MySQL installation:
```bash
  spring.datasource.url=jdbc:mysql://localhost:3306/crudappdb
  spring.datasource.username=root
  spring.datasource.password=root
```
7. Build the project: Open a command prompt, navigate to the root directory of the cloned project, and run the following command to build the project:
```bash
  mvn cean install
```
8. Run the Spring Boot backend from SpringbootBackendApplication.
This will start the backend server on http://localhost:8080/api/v1/employees .
9. Run the Angular frontend: Open a new command prompt, navigate to the angular-frontend directory of the cloned project, and run the following command to install the required dependencies:
```bash
  npm install
```
10. After the installation is complete, run the following command to start the Angular development server:
```bash
  ng serve
```
11. Access the app: Open a web browser and navigate to http://localhost:4200 to access the full-stack app.
