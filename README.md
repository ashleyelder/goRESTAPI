# Movies REST API in Go
###### Have you ever wanted to track what movies you watch?
###### Read, create, update, and delete movie entries. 

## To Start

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
