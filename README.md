# E-Commerce API Testing Project

## Overview

This project demonstrates API testing of an E-Commerce application using Postman. The collection covers authentication, user management, products, cart functionality, and negative test scenarios.

## Tools Used

* Postman
* JavaScript (Postman Test Scripts)
* Newman
* GitHub

## Project Structure

### Authentication

* Valid Login
* Invalid Login
* Missing Password
* Missing Username

### User

* Get User Profile
* Get User By ID
* Search User

### Products

* Get Products
* Get Single Product
* Search Product
* Filter Products
* Sort Products

### Cart

* Add To Cart
* View Cart
* Update Cart
* Delete Cart

### Negative Tests

* Invalid Product ID
* Unauthorized Access
* Invalid Request Body

## Test Coverage

* Status Code Validation
* Response Body Validation
* Authentication Testing
* Response Time Validation
* Content-Type Validation
* Positive Test Scenarios
* Negative Test Scenarios
* Environment Variables
* Dynamic Data Handling
* Request Chaining

## Key Features

* Extracts and stores authentication token using environment variables.
* Uses dynamic variables such as user_id and product_id across requests.
* Implements collection-level validations for common checks.
* Covers both successful and failure scenarios.
* Supports execution through Newman CLI.

## How to Run

### Using Postman

1. Import the collection and environment files.
2. Select the appropriate environment.
3. Run the collection using Collection Runner.

### Using Newman

```bash
newman run "E-com API Project.postman_collection.json"
```

or

```bash
newman run "E-com API Project.postman_collection.json" -e "E-com Environment.postman_environment.json"
```

## Learning Outcomes

* REST API Testing
* Authentication Testing
* API Response Validation
* Environment Variable Management
* Request Chaining
* Automated Collection Execution with Newman

## Author

Manas Pal
