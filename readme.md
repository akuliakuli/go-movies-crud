# Go Movies API

This project is a basic RESTful API built with Go and the `gorilla/mux` router. It allows users to perform CRUD (Create, Read, Update, Delete) operations on a list of movies.

## Features

- **Retrieve All Movies**: Fetches a list of all movies.
- **Retrieve a Single Movie**: Fetches details of a specific movie by its ID.
- **Create a Movie**: Allows users to add a new movie to the list.
- **Update a Movie**: Updates the information of an existing movie.
- **Delete a Movie**: Removes a movie from the list by its ID.

## Running the Project

1. **Install Go**: If you don’t have Go installed, [download and install it](https://golang.org/doc/install).

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/go-movies-api.git
   ```

3. **Navigate to the Project Directory**:
   ```bash
   cd go-movies-api
   ```

4. **Install Dependencies**:
   Ensure that the `gorilla/mux` package is installed:
   ```bash
   go get -u github.com/gorilla/mux
   ```

5. **Run the Server**:
   ```bash
   go run main.go
   ```

6. **Access the API**:
   The server will start at `http://localhost:8080`, and you can interact with the API through this base URL.

## Example Movies

Two sample movies are preloaded into the server:

1. **Interstellar**
   - Director: Christopher Nolan
   - ISBN: 4025413

2. **Jay and Silent Bob**
   - Director: Mike Wazowski
   - ISBN: 42341234


