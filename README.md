# Ortege API Postman Collection
Welcome to the Ortege API Postman Collection! This collection contains pre-configured requests to interact with the Ortege API, enabling seamless access to a variety of blockchain data through REST, GraphQL, and WebSocket endpoints. With this collection, you can easily test and integrate Ortege’s high-performance data sources into your applications.

# Getting Started
## Prerequisites
* Postman: Make sure you have Postman installed.
* Ortege API JWT Token: You’ll need a valid JWT token to authenticate API requests. Please contact the Ortege team to obtain your token.

## Setting Up the Collection
### Import the Collection:

* Download the Ortege API Postman Collection JSON file.
* In Postman, click on Import and select the downloaded JSON file.

### Create an Environment:

* In Postman, go to Environments and click + New Environment.
* Name it “Ortege API Environment” or similar.
* Add the following variables:
* * jwt_token: Paste your JWT token here. This is required for authenticated requests.
* * base_rest_url: Set to https://api-staging.ortege.ai/cubejs-api/v1 for REST requests.

### Set Up Authorization:

* In the imported collection, go to the Authorization tab.
* Select Bearer Token as the type.
* Set the Token field to `{{jwt_token}}` to use your environment variable.
* Switch to the Ortege Environment. Before running requests, select the newly created “Ortege API Environment” from the environment dropdown in Postman’s top-right corner.

# Additional Resources
For more details on the Ortege API and Cube query formats, refer to the following:

[Ortege API Documentation](https://docs.ortege.ai)
