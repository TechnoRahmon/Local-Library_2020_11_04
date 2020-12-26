# Local-Library_2020_11_04
It is a backend project, using node express, js. It does not have any front-end design, so you have to use the postman Or similar program to use the project

# Purpose:

Implement RestFul API with authentication, Access Token Encryption &
Decryption, & Role based authentication with JWT

# The Tasks of this project are :

-Design an API which has 3 roles: Guest, BasicUser, AdminUser.

-Guest will have access to Index, AddUser, GetBooks and GetBook actions.

-BasicUser will have access to Index, AddUser, GetBooks, GetBook, RateBook actions.

-AdminUser will have access to Index, AddUser, GetUsers, GetUser, UpdateUser, RemoveUser,
RateBook, GetBooks, GetBook, AddBook, UpdateBook, and RemoveBook actions.

-use MongoDB/mongoose

-Add bd/Schema Level validation

-implement password hashing using bcrypt, while serving the user’s data into the MongoDB database.

# The endpoints that are implemented :

• POST /api/books: Add new books

• POST /api/user: Add new user

• GET /api/books: list all books

• GET /api/users: list all users

• GET /api/book/{id}: retrieve a single book information

• GET /api/user/{id}: retrieve a single user information

• DELETE /api/book/{id}: delete a single book

• DELETE /api/user/{id}: delete a single user

• PUT /api/book/{id}: update a single book

• PUT /api/book/{id}: update ratings of a single book

• PUT /api/user/{id}: update a single user
 

# To Run The Project

We are using local Mongo database, so you need to install the mongodb in your system and make sure that it's running at port 27017

After cloning the project go to main folder then run in the terminal :

### ``` npm install ```

then:

### ``` npm start ```

you gonna use http://localhost:7000 end point to send the requests from the Postman 
