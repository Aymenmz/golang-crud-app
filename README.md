## Movies Server API Routes

| **HTTP Method** | **Endpoint**        | **Description**                      | **Function**  | **Route**                                                    |
|-----------------|---------------------|--------------------------------------|---------------|---------------------------------------------------------------|
| GET             | `/movies`           | Get all movies                       | `getMovies`   | `r.HandleFunc("/movies", getMovies).Methods("GET")`           |
| GET             | `/movies/{id}`      | Get a specific movie by ID           | `getMovie`    | `r.HandleFunc("/movies/{id}", getMovie).Methods("GET")`       |
| POST            | `/movies`           | Create a new movie                   | `createMovie` | `r.HandleFunc("/movies", createMovie).Methods("POST")`        |
| PUT             | `/movies/{id}`      | Update an existing movie by ID       | `updateMovie` | `r.HandleFunc("/movies/{id}", updateMovie).Methods("PUT")`    |
| DELETE          | `/movies/{id}`      | Delete a specific movie by ID        | `deleteMovie` | `r.HandleFunc("/movies/{id}", deleteMovie).Methods("DELETE")` |
