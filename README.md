# Go Programming

This repository serves as a learning resource for Go (Golang), following the tutorials provided by [freeCodeCamp](https://youtu.be/jFfo23yIWac?si=7M4hUPmXG7Rhmkit). The tutorial covers 11 projects aimed at helping learners gain practical experience with Go programming.

## Simple HTTP Server with Golang

This repository contains a simple HTTP server built using Go (Golang). The server serves static files and handles two endpoints: **/form** and **/hello**.

/form
This endpoint handles POST requests and expects form data with fields name and address. Upon receiving a POST request, it prints the submitted data to the response.

Example:

bash
Copy code
curl -X POST -d "name=John&address=123 Main St" http://localhost:8080/form
/hello
This endpoint handles GET requests and simply responds with "hello".

Example:

bash
Copy code
curl http://localhost:8080/hello
Serving Static Files
The server also serves static files located in the ./static directory. You can place your HTML, CSS, JavaScript, or any other static files in this directory, and they will be served by the server.
