# basic-php-crud


Basic PHP CRUD with Authentication
This repository contains basic CRUD (Create, Read, Update, Delete) operations with basic authentication for educational purposes.

Branches:
basic-crud: CRUD operations without authentication.
basic-crud-auth: CRUD operations with basic authentication.
Learning Roadmap
🚀 basic-crud Branch
Import Database
Start by importing the basic_crud.sql file into your database. This sets up the necessary tables for CRUD operations.

Database Connection
Review the database connection logic in the database.php file. This file will show how to establish a connection to the database.

Folder Structure & CRUD Operations

Check the index.php file. This will give you an overview of the folder structure and demonstrate how the CRUD operations are implemented (listing products, creating new products, editing, and deleting).
CRUD Implementation

Explore the following files:
create-product.php: Contains logic for adding new products to the database.
edit-product.php: Allows you to modify the product information.
delete-product.php: Handles product deletion from the database.
🔒 basic-crud-auth Branch
This branch includes authentication features. Here's a breakdown of how the session-based authentication logic is integrated with the CRUD operations:

User Registration

Begin by reviewing the register.php file. This contains logic for creating a new user account.
Understand how the form is submitted and how the user data is validated and saved to the database.
User Login

Check the login.php file next. This file demonstrates how users log in with their credentials, check for validity, and start a session.
Focus on how login credentials are validated against the stored database and how the session is created.
Revisit Registration & Login Logic

Go through both register.php and login.php again, as there are multiple parts of the logic that need to be understood, including input sanitization, hashing passwords, and setting up sessions.
Session Management

Review the index.php file for an example of how user sessions are handled. You'll see how to check if a user is logged in and how to limit access to CRUD operations based on the session status.
Logout

Visit the logout.php file to understand how the session is destroyed. This is crucial to ensure users can securely log out and the session is properly terminated.
CRUD with Authentication

Finally, check out the CRUD-related files (create-product.php, edit-product.php, delete-product.php) again to understand how authentication is incorporated into these pages.
Learn how to restrict access to these pages if the user is not logged in and how to implement user-specific data access.
Key Concepts to Understand:
Session Management: Sessions are used to keep users logged in and identify them across requests.
Data Validation and Sanitization: Ensure user inputs are secure and prevent common vulnerabilities (e.g., SQL injection).
Authentication Flow: Understand the registration, login, and logout flow. Review how user authentication controls access to CRUD operations.
CRUD Logic: Learn how to handle basic CRUD operations and how to interact with a MySQL database using PHP.
