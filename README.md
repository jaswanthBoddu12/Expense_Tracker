# Expense Tracker Application

A web-based application for tracking personal expenses built with Spring Boot, Thymeleaf, and Spring Security.

## Features

- User registration and authentication
- Secure login/logout functionality 
- Add, edit, and delete expenses
- Create custom expense categories
- Filter expenses by date and category
- Download expense reports

## Technology Stack

- Java 17
- Spring Boot
- Spring Security
- Spring Data JPA
- Thymeleaf
- MySQL/H2 Database
- Maven

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 17 or higher
- Maven 3.6 or higher
- MySQL (or you can use H2 in-memory database for testing)

### Running the Application

1. Clone the repository
2. Configure the database connection in `src/main/resources/application.properties`
3. Build the project: `mvn clean install`
4. Run the application: `mvn spring-boot:run`
5. Access the application at `http://localhost:8080`

### Default Login

The application creates a default user on startup:
- Email: admin@example.com
- Password: password

## Usage

1. Register for a new account using the sign-up form
2. Log in with your credentials
3. Navigate to the "Expenses" page to add, view, or edit expenses
4. Use the "Categories" page to add or manage expense categories
5. Filter expenses by date, month, or category on the expenses page
6. Download your expense data as a CSV file for further analysis

## Security Features

- Passwords are securely hashed using BCrypt
- Session management
- CSRF protection
- User-specific data isolation (users can only see their own expenses)

## License

This project is open source and available under the [MIT License](LICENSE).

## Demo Video

Check out this video to see a live demonstration of the Expense Tracker app:
[Expense Tracker Demo](https://youtu.be/IlUs0ESfFK4)

## Features

- Adding, updating, deleting operations for expenses.
- View summaries of expenses in a table, and a summary of the total amount spent.
- Filtering expenses by year, month, and expense type.
- Pagination
- Customize your expense categories
- Download expenses as CSV file.
- Responsive design 

## Technologies Used

- Java 17.0
- Spring Boot 3
- Spring Data JPA (for data access)
- Thymeleaf (for server-side templating)
- MySQL (as the database)
- Maven (for build and dependency management)
- HTML, CSS, Bootstrap
- Server is Tomcat, built-in server of Spring Boot.

## Getting Started

1. Clone the repository to your local machine.
2. Open the project in your preferred Java IDE.
3. Make sure you have MySQL installed on your machine
4. Create a MySQL database named `budgetpal` or update the database configuration in `src/main/resources/application.properties` with your own database settings.
6. Build and run the application using Maven via `mvn spring-boot:run` command or via IDE.
7. Access the app in your browser at `http://localhost:9191`. You can change the serverport in application.properties file.



