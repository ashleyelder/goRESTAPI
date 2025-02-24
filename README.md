# Go REST API
## Track Movies Watched
This simple REST API built with Go was my first experience trying Go. Basic CRUD operations manage a slice of movies. The project uses the `gorilla/mux` router for handling HTTP requests and serves as a learning exercise for building APIs in Go.

## To Start
Not ideal... see 'Potential Next Steps' below

```
# Install mux router
go get -u github.com/gorilla/mux
```

```
go build && ./goRESTAPI-master
```

## Endpoints

**Get All Movies**
```
GET http://localhost:8000/movies
```

**Get Single Movie**
```
GET http://localhost:8000/movies/{id}
```

**Create Movie**
```
POST http://localhost:8000/movies
```

**Update Movie**
```
PUT http://localhost:8000/movies/{id}
```

**Delete Movie**
```
DELETE http://localhost:8000/movies/{id}
```

## Potential Next Steps
* **Go Modules and Project Structure**: This project was originally written before the introduction of Go Modules. Bring it up to date.
* **Database Integration**: Replace hardcoded data with a database.
* **Input Validation**: Validate incoming requests to ensure data integrity.
* **Testing**: Write unit tests.
* **Dockerization**: Create a Dockerfile for easy deployment.
* **Authenticatio**n: Add user authentication and authorization.
