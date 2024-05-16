# Stockmonitorbackend
Overview
The Stock Monitoring Platform is a web application designed to help users track and monitor stock prices in real-time. The platform enables users to create and manage personalized watchlists of stock symbols, view the latest stock values on a dashboard, and authenticate securely to manage their data. The backend of the application is built using Java with the Spring Boot framework, while the frontend leverages React with TypeScript and Material UI for a modern, responsive user interface.

Features
User Authentication:

Secure user registration and login functionality.
Password hashing to ensure user data protection.
Watchlist Management:

Users can create, update, and delete multiple watchlists.
Each watchlist can contain multiple stock symbols.
Dashboard:

Real-time display of the latest stock prices for the symbols in the user’s watchlist.
Integration with the Alpha Vantage API to fetch real-time stock data.
Concurrent User Support:

The platform is designed to handle multiple users simultaneously, each with their own watchlists and stock data.
Database Integration:

PostgreSQL is used to store user data and watchlist information.
Secure and efficient data handling with Spring Data JPA.
Technologies
Backend:

Java: Core language for backend development.
Spring Boot: Framework for building the backend RESTful API.
Spring Security: For securing user authentication and authorization.
PostgreSQL: Relational database for storing user and watchlist data.
Hibernate: ORM tool used with Spring Data JPA for database operations.
JUnit & Mockito: For unit and integration testing.
Frontend:

React: JavaScript library for building user interfaces.
TypeScript: Superset of JavaScript that adds static typing.
Material UI: UI framework for styling and component functionality.
Axios: For making HTTP requests to the backend API.
