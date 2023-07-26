# API Testing Using Postman

# Overview
This project provides an example for testing RESTful APIs with Postman. It can be used to kickstart testing of other RESTful APIs with minimal changes to the project.This web service provides booking functionalities for a fictional hotel. You can interact with the API using standard HTTP methods, following the principles of Representational State Transfer (REST). It offers various endpoints for authentication, creating, managing, and retrieving bookings.

# Why Use Postman?
Postman is a widely used and user-friendly API testing tool. It simplifies the process of creating and sending requests while also allowing users to inspect the responses, making it highly favored for exploratory and manual API testing. However, it offers more capabilities than just that and is frequently underestimated as a tool for automated API testing.

# Base URL
The base URL for accessing the Restful Booker API is:
https://restful-booker.herokuapp.com

# Postman Test Suite
The Postman test suite here is made up of two separate files:
1. Flight8.postman_collection.json
2. bug8Environment.postman_environment.json

# Newman Commands

Step-1
for installing npm:
npm install -g newman 

Step-2
newman run Flight8.postman_collection.json -e bug8Environment.postman_environment.json

Step=3
for generating report
newman run Flight8.postman_collection.json -e bug8Environment.postman_environment.json  -r cli,htmlextra

# Project Interface in Postman
![api1](https://github.com/Sajid186/API-Testing-Postman/assets/69852376/11dff42a-a5d9-4e25-9d58-69daf03e030a)

# Report Interface
![api2](https://github.com/Sajid186/API-Testing-Postman/assets/69852376/e3757134-7bec-41ee-96ca-e79b6734fe43)
![api3](https://github.com/Sajid186/API-Testing-Postman/assets/69852376/a4a102da-f4a2-406f-8449-b28be409d2c5)
![api4](https://github.com/Sajid186/API-Testing-Postman/assets/69852376/679c844a-48fe-4a7c-a2a4-6214eb646692)
![api5](https://github.com/Sajid186/API-Testing-Postman/assets/69852376/ef449def-df5b-430e-9fc9-e4c09d5487bf)

# NB
The Report is in HTML format. Please download the report and open it using any browser.
