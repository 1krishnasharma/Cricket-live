# Cricket Backend API

This project is a Java Spring Boot application that serves as a backend API for managing cricket matches and related data.

## Features

- **Live Matches:** Endpoint to retrieve a list of live cricket matches.
- **All Matches:** Endpoint to retrieve all cricket matches.
- **Point Table:** Endpoint to retrieve the point table of ongoing tournaments.

## Endpoints

- `GET /match/live`: Retrieve live cricket matches.
- `GET /match`: Retrieve all cricket matches.
- `GET /match/point-table`: Retrieve the point table of ongoing tournaments.

## Setup

1. **Clone the Repository:**
    ```
    git clone https://github.com/yourusername/cricket-backend.git
    ```

2. **Build the Project:**
    ```
    mvn clean install
    ```

3. **Run the Application:**
    ```
    java -jar target/cricket-backend.jar
    ```

4. **Access the API:**
    The API will be available at `http://localhost:8080`.

## Dependencies

- Spring Boot
- Maven

## Configuration

The application can be configured via `application.properties` file located in `src/main/resources`. Here you can configure database connection details, server port, etc.

## Usage

This backend API can be integrated with front-end applications, mobile apps, or other services to fetch live cricket match data, all match data, and point tables for ongoing tournaments.

## Contributors

- Your Name <youremail@example.com>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
