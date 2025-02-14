# Album CRUD App

This project is a simple CRUD (Create, Read, Update, Delete) application for managing albums using the Gin web framework in Go.

## Prerequisites

- Go 1.23.5 or later
- Git

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/album-crud-app.git
    cd album-crud-app
    ```

2. Install the dependencies:
    ```sh
    go mod tidy
    ```

## Running the Application

1. Start the server:
    ```sh
    go run main.go
    ```

2. The server will start on `localhost:8080`. You can access the endpoints using a tool like `curl` or Postman.

## Endpoints

- `GET /albums` - Retrieve a list of all albums
- `GET /albums/:id` - Retrieve a specific album by ID
- `POST /albums` - Create a new album
- `PUT /albums/:id` - Update an existing album by ID
- `DELETE /albums/:id` - Delete an album by ID

## Example

To get a list of all albums, you can use the following `curl` command:
```sh
curl http://localhost:8080/albums
```

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.