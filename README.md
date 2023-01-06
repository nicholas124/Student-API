#### Spring Boot REST API for Student Management

This API allows you to create, retrieve, update, and delete student records, each of which consists of a student name and an address. It is built using Spring Boot, an open-source framework for creating stand-alone Java applications.

To use this API, you can send HTTP requests to the following endpoints:

* POST /student/add: creates a new student record with the given name and address in the request body.
* GET /students/getAll: retrieves all the students records.
## The below are yet to be implemented but you can go ahead and try
* PUT /students/{id}: updates the student record with the given ID using the name and address in the request body.
* DELETE /students/{id}: deletes the student record with the given ID.
You can also use the API to list all student records by sending a GET request to /students.

This API is intended to be used with a React frontend application, which can make HTTP requests to the API endpoints to perform CRUD (create, read, update, delete) operations on the student records.
