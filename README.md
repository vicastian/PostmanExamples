# Beon assessment
Exercises from technical assessment from Victor Escobar

## Notes:
1. The exercise 1, 2, 3 and 4 are found under the request "Retrieve list of users" in the test tab. 
2. The exercise 5, 6, 7 are found under the request "Get user by id" in the test tab. 
3. The exercise 8, 9, 10 are found under the request "Create new user" in the test tab. 

## Instructions:
You have been assigned to automate the testing of the ReqRres API, which simulates user
management functionality.
Your task is to create an automated test script using Postman that performs the following:

1. Send a GET request to the ReqRes API endpoint `/users` to retrieve a list of users.
2. Validate the response status code to ensure it is a successful response (e.g., 200 OK).
3. Validate the response body to ensure it meets the following criteria:
  ** The response should contain an array of users.
  ** Each user should have a unique `id`, `email`, `first_name`, and `last_name`.
4. Extract the value of the `id` from one of the users in the response and store it as a variable.
5. Send a GET request to the ReqRes API endpoint `/users/{id}`, where `{id}` is the extracted
user ID from step 4.
6. Validate the response status code to ensure it is a successful response.
7. Validate the response body to ensure it contains detailed information about the specific user
with the matching ID.
8. Send a POST request to the ReqRes API endpoint `/users` to create a new user. Include the
necessary request body with the user's information (e.g., `email`, `first_name`, `last_name`).
9. Validate the response status code to ensure the user creation was successful (e.g., 201
Created).
10. Validate the response body to ensure it contains the newly created user's information.
Your solution should include:
  - A Postman collection with the test script that performs the steps mentioned above.
  - Test assertions to validate the expected responses and conditions.
  - Usage of variables and environment configurations as needed.
  - Appropriate error handling and reporting in case of failures.

Please provide your automated test script using Postman for this API testing challenge, including
any necessary documentation or notes to explain your approach and reasoning in a
README.md file.
Upload your script and documentation to a GitHub repository and share it at the end of the
interview.
Utilize the ReqRes API documentation (https://reqres.in/) to understand the available
endpoints, request and response formats, and any additional details.
