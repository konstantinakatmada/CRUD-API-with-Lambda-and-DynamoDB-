# CRUD-API-with-Lambda-and-DynamoDB

This project demonstrates the implementation of a serverless API that performs CRUD operations (create, read, update, delete) on items stored in a DynamoDB table using AWS Lambda functions. The API I created allows you to manage data effectively and easily.

## Accessing the DynamoDB Table

To access the DynamoDB table used in this project, follow the steps below:

### Option 1: Using AWS IAM User

1. Contact the [project owner](https://github.com/konstantinakatmada) to request access as an AWS IAM user.
2. The project owner will create an AWS IAM user through the AWS Management Console.
3. The project owner will assign appropriate permissions to the IAM user, including access to the DynamoDB table.
4. The project owner will generate the Access Key and Secret Key for the IAM user and provide them to you.
   - **Note:** Do not share the Access Key and Secret Key publicly, such as in a GitHub repository, to ensure security. Make sure that any file that contains sensitive information is added to the .gitignore.

### Option 2: Using IAM Role-Based Access

1. Contact the [project owner](https://github.com/konstantinakatmada) to request access using IAM role-based access.
2. The project owner will set up an AWS IAM role with the necessary permissions to access the DynamoDB table.
3. You can assume this IAM role using your own AWS credentials and access the table.
   - This approach provides a more secure way of accessing the table without sharing sensitive credentials publicly.

Choose the option that suits your needs and contact the [project owner](https://github.com/konstantinakatmada) to request access to the DynamoDB table.

## Accessing the API

To interact with the API, you can utilize the following routes:

- `PUT /items`: Creates a new item in the DynamoDB table.
- `GET /items`: Retrieves all items from the DynamoDB table.
- `GET /items/{id}`: Retrieves a specific item by its ID from the DynamoDB table.
- `DELETE /items/{id}`: Deletes a specific item by its ID from the DynamoDB table.

Please note that the actual IDs of the routes and integrations are not disclosed here for security reasons.

## Integration Details

The routes mentioned above are integrated with AWS Lambda functions using a shared integration ID. This integration enables the execution of the corresponding Lambda functions when requests are made to the API routes.

Sharing the integration IDs or any sensitive information publicly, such as in a GitHub repository, is not recommended for security reasons. Therefore, specific IDs are not provided here.

For further details on the API implementation, code structure, and setup instructions, please refer to the documentation or contact the [project owner](https://github.com/konstantinakatmada).

