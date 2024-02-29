
# MarketPlace Application

A simple MarketPlace application built with Spring Boot, PostgreSQL, Angular and JWT for handling access and refresh tokens.

## Features

- User registration and authentication.
- Product listing and searching.
- Buying and selling functionality.
- JWT-based secure access and refresh token handling.

## Prerequisites

Make sure you have the following tools installed before setting up the application:

- Java Development Kit (JDK)
- Apache Maven
- PostgreSQL

## Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/confusedGustas/MarketPlace
    cd MarketPlace
    ```

2. **Configure PostgreSQL:**

   - Create a new database.
   - Leave the default settings as it is, Spring Boot will create the needed tables.
   - If you want configurate the settings, you can do it so by accessing the `application.yaml` file

    ```datasource:
    url: jdbc:postgresql://localhost:5432/marketplace
    username: postgres
    password: postgres
    ```

3. **Build and run the application:**

    ```bash
    mvn spring-boot:run
    ```

   The application will start on `http://localhost:8080`.

## Usage

- Access the application through your browser (http://localhost:4200)
- Register as a new user and log in to start

## License

This project is licensed under the [MIT License](./LICENSE).

## Note

I am fully aware of the problems in this project. There are a number of mistakes here and there, and there are certain areas that really need to be improved, such as handling duplicate API calls and caching them, handling image compression and decompression, and generally using API endpoints more wisely. However, the main goal was to learn more about JWT authentication and improve Spring security. Think of that mission as accomplished!
