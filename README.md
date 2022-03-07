# msd-2022-spring-cs477-homework6
# Lab 6 - Authentication & Authorization
1. Continue Lab 6 based on Lab 5 to implement the features below for RESTful Application:
    1. Create some users in your system for the next login function
    2. Add a login feature which username and password. If logged in successfully, return JWT, otherwise, error message.
    3. For all requests to get the houses' information, they have to be authenticated. If call APIs without JWT, return 401 unauthorized. With incorrect JWT, return 403 Forbidden. Only with correct, return JSON data. Using middleware to implement this
