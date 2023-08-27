---

# Go JWT MongoDB Gin Gonic Authentication Project

## Overview

This project demonstrates how to create a secure web application in Go, utilizing JSON Web Tokens (JWT) for authentication, MongoDB as the database, and Gin Gonic for routing and middleware. 

## Features

- User registration and login
- JWT-based authentication
- MongoDB for data storage
- Secure password hashing
- Middleware for authentication and authorization

## Prerequisites

Before running the project, ensure you have the following installed:

- Go (version >= 1.15)
- MongoDB (version >= 4.0)
- Git

## Getting Started

1. Clone the repository:

   ```shell
   git clone https://github.com/samriddha-basu-cloud/Authentication_using_Go_JWT_MongoDB_Gin_Gonic.git/
   cd Authentication_using_Go_JWT_MongoDB_Gin_Gonic
   ```

2. Install project dependencies:

   ```shell
   go mod download
   ```

3. Set up your MongoDB database and update the connection settings in `config.go`.

4. Run the application:

   ```shell
   go run main.go
   ```

## Usage

- Register a new user using `/api/register` with a POST request.
- Authenticate and receive a JWT token at `/api/login`.
- Access protected routes by including the JWT token in the Authorization header.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

## Acknowledgments

- [Gin Gonic](https://gin-gonic.com/)
- [MongoDB Go Driver](https://pkg.go.dev/go.mongodb.org/mongo-driver)
- [github.com/dgrijalva/jwt-go](https://github.com/dgrijalva/jwt-go)

## Contact

For questions or support, please contact [sb289@srmist.edu.in](mailto:sb2899@srmist.edu.in)

---
