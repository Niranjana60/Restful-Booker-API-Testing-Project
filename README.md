# Restful-Booker-API-Testing-Project
This project demonstrates REST API testing using Restful Booker, a public API designed for testing and practice. 
The testing framework uses Postman and Newman to automate and validate API functionality across various endpoints.

Tools Used: Postman, Newman, Node.js, HTML Reporter

Focus: Functional API testing using manual and automated approaches

Includes Auth: Token-based authentication for secure endpoints

 Report Generation: HTML reports via Newman CLI

Endpoints Tested

Method	Endpoint	Description
POST	/auth	Generate auth token

GET	/booking	Retrieve booking IDs

GET	/booking/{id}	Retrieve specific booking

POST	/booking	Create a new booking

PUT	/booking/{id}	Update existing booking

PATCH	/booking/{id}	Partially update booking

DELETE	/booking/{id}	Delete a booking

Sample Report

 You can view a full HTML report in the reports/ folder after running the collection.

