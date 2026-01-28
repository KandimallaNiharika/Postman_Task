# Task 2-API Testing Using Postman  

*Company:*CODTECH IT SOLUTIONS

*Intern Name:*Kandimalla Niharika

*Intern Id:*CTIS2057

*Domain:*Software Testing

*Duration:*4 Weeks

*Mentor:*Neela Santosh

PROJECT TITLE: API Testing Using Postman  

## Introduction
API (Application Programming Interface) testing is a type of software testing that focuses on verifying whether APIs function correctly, reliably, and securely. Postman is a popular tool used for testing RESTful APIs by sending HTTP requests and validating responses.

This task involves testing RESTful APIs using Postman for data creation and data retrieval operations. The task demonstrates the usage of POST and GET methods along with response validation.

## Objective
The main objective of this task is:
- To understand RESTful API concepts
- To perform API testing using Postman
- To validate API responses using status codes and response data
- To document test results clearly

## Tools and Technologies Used
- **Postman** – For sending API requests and validating responses
- **RESTful APIs** – DummyJSON public API
- **HTTP Methods** – POST and GET
- **Data Format** – JSON

## APIs Tested

### 1. Create User API
- **Method:** POST  
- **Endpoint:** https://dummyjson.com/users/add  
- **Description:**  
  This API is used to create a new user by sending user details in JSON format. It simulates data creation and returns a success response along with user information.
- **Expected Response:**  
  200 OK or 201 Created with user details.

### 2. Get Users API
- **Method:** GET  
- **Endpoint:** https://dummyjson.com/users  
- **Description:**  
  This API retrieves a list of users from the server. It is used to verify data retrieval functionality.
- **Expected Response:**  
  200 OK with a list of users in JSON format.

## Testing Methodology
- Requests were created and executed using Postman.
- Headers such as `Content-Type: application/json` were added.
- Request bodies were sent in raw JSON format for POST requests.
- Responses were analyzed using status codes and response body.
- Test scripts were used to validate successful execution.

## Deliverables
- Postman Collection (exported in JSON format)
- README documentation
- API Test Results text file
- Screenshots of API execution (optional)

## Conclusion
The APIs were successfully tested using Postman. Both POST and GET requests returned expected responses and correct HTTP status codes. This task provided hands-on experience in RESTful API testing and improved understanding of API request-response mechanisms.


<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/52f51f69-8ea2-4f2f-be76-ef96103c9ca3" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/4e5218d3-a97c-499f-9834-0f9b9f5fb7db" />
