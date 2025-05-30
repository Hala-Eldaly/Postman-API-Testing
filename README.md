# ReqRes API Testing Project

This project is for testing ReqRes APIs using Postman. The project includes:

- **Collection**: Contains requests (GET, POST, PUT, DELETE) with tests to verify responses.
- **Environment**: Includes the variable `base_url` to facilitate URL management.

## How to use the project:

1. Import the collection file (`ReqRes_API_Collection.json`) into Postman.
2. Import the environment file (`ReqRes_Environment.json`) and select it as the active environment.
3. Run the requests from the collection and check the tests in the "Tests" tab.

## Examples of tests:

- For the "List Users" request:
  - Checks that the status code is 200.
  - Checks that the response contains an array called `data`.
  - Checks that the response time is less than 500 milliseconds.
