1)Admin Functionality:

->Admin login and dashboard.
->Customer registration and management.
->Account closure and transaction history.
->Customer Functionality:

2)Customer login and dashboard.
->Deposit, withdrawal, and balance management.
->Transaction history and account closure.
->Project Structure

3)The project follows a structured MVC (Model-View-Controller) architecture:

Servlets: Handles HTTP requests and implements application logic.
DAOs (Data Access Objects): Interfaces with the database.
Models: Defines data objects used throughout the application.
Utility classes: Manages database connections (DBConnection).
Web Content (WebContent/):

JSP Pages: User interfaces for admin and customer operations.
WEB-INF: Configuration files and libraries.


Set up the database:

Install MySQL and create a database named banking_app.
Import the database schema from database_schema.sql using MySQL Workbench or command line.
Configure the database connection:

Modify DBConnection.java in src/com/yourpackage/util/ with your MySQL credentials.
Deploy the application:

Use Apache Tomcat or another servlet container to deploy the WAR file (BankingApplication.war) found in the dist/ directory.
Access the application:

Open a web browser and navigate to http://localhost:8080/BankingApplication/.
Technologies Used
Java Servlets
JSP (JavaServer Pages)
MySQL
Apache Tomcat
HTML, CSS
Contributing
Feel free to fork this repository, submit pull requests, or open issues for any bugs or feature requests.
