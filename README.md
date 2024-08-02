# ReqRes API Tests

This project contains a collection of API tests for the [ReqRes API](https://reqres.in/), designed to be run using [Newman](https://github.com/postmanlabs/newman) and GitHub Actions. The tests cover various endpoints of the ReqRes API, ensuring that the API behaves as expected.

# Running Tests Locally
You can run the Postman collection locally using Newman with the following command:
```sh
newman run collections/ReqRes_API_Tests.postman_collection.json --environment environments/environment.json
```
# Running Tests with GitHub Actions

The project is set up to automatically run the Postman tests using GitHub Actions on each push to the main branch or when a pull request is opened. 
