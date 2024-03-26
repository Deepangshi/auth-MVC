# Auth ASP.NET MVC Project

## Project Overview

This project focuses on developing user authentication system using ASP.NET Core 8, including the implementation of user registration, authentication, authorization, and user profile management. All of these features can be easily implemented in MVC application with the help of identity library. 

## Technologies Used

- ASP.NET MVC- Microsoft framework for web development, emphasizing a separation of concerns.
- C#- Microsoft's programming language, versatile for various applications.
- Entity Framework- Data access technology.
- MSSQL- Microsoft's relational database management system.
- Identity UI- Authentication library. 

## Folder Structure

- /Areas/Identity- To organize the project into smaller functional groups, each potentially having its own Models, Views, and Controllers.
- /Data- The application's data access layer, including Entity Framework contexts and model configurations. /authDBContext.cs:- defining the database context for authentication, linking models to database tables related to user authentication and authorization.
- /Pages: Holds Razor pages or additional views; /login.cshtml: The Razor page for user login, /register.cshtml: The Razor page for user registration.
- /Controllers: Houses classes that handle user input, process requests, and return responses.
- /Models: Contains classes representing application data and logic for managing the data.
- /Views: Stores files for the application's user interface.
  
