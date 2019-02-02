# webForu

    user data is stored in MongoDB, with the passwords hashed
    CRUD functions are built in an Express API — Create (register), Read (login, get profile), Update, Delete
    an Angular application calls the API and deals with the responses
    the Express API generates a JSON Web Token (JWT, pronounced “Jot”) upon registration or login, and passes this to the Angular application
    the Angular application stores the JWT in order to maintain the user’s session
    the Angular application checks the validity of the JWT when displaying protected views
    the Angular application passes the JWT back to Express when calling protected API routes.
m
