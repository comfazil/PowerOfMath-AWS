
# Power of Math - AWS

This project demonstrates the integration of multiple AWS services to create a web application that calculates the power of a number using AWS Amplify, AWS Lambda, API Gateway, and DynamoDB. The web application is hosted on AWS Amplify, which provides a scalable and secure hosting environment for web applications.

## Features
### Web Application:
The project utilizes AWS Amplify to create and deploy a web application.
### Lambda Function: 
A Lambda function is created to calculate the power of a number.
### API Gateway: 
An API Gateway is set up to expose the Lambda function as a RESTful API endpoint.
### DynamoDB: 
The Lambda function stores the calculated results in a DynamoDB table.
### IAM Policy: 
The Lambda function is granted permissions to access and manipulate items in the DynamoDB table using an inline IAM policy. 

## Getting Started
To deploy and run the project locally, follow these steps:

1. Set up AWS Amplify: Install and configure the AWS Amplify CLI if you haven't already.
2. Create Web App: Use the Amplify CLI to create a new web app.
3. Create Lambda Function: Write and deploy a Lambda function to calculate the power of a number.
3. Set up API Gateway: Configure API Gateway to trigger the Lambda function.
4. Create DynamoDB Table: Create a DynamoDB table to store the calculation results.
5. IAM Policy: Attach an inline IAM policy to the Lambda function to grant permissions to access DynamoDB.
6. Invoke API: Invoke the API endpoint from the index file of the web application to perform the power calculation.
### Usage
Once the project is deployed, users can access the web application and enter a number and its power to calculate the result. The result will be stored in the DynamoDB table for future reference.

### Resources
AWS Amplify Documentation
AWS Lambda Documentation
Amazon API Gateway Documentation
Amazon DynamoDB Documentation



## Screenshots: 
![test11](https://github.com/comfazil/PowerOfMath-AWS/assets/101056131/d63c7847-de5e-492b-81a7-02c655b283c4)
![test1](https://github.com/comfazil/PowerOfMath-AWS/assets/101056131/2f877cc0-3cf4-4e4e-b5da-351ea50b4923)
![test](https://github.com/comfazil/PowerOfMath-AWS/assets/101056131/c297c43d-6880-447c-8f04-d4a78fa876cd)
![policy](https://github.com/comfazil/PowerOfMath-AWS/assets/101056131/8ef2f1c7-a9e6-48df-a478-af1e1e71760d)
![lambda](https://github.com/comfazil/PowerOfMath-AWS/assets/101056131/1f849e3e-ad70-4b37-9d5d-39e7b058c023)
![dynamo](https://github.com/comfazil/PowerOfMath-AWS/assets/101056131/2b52d331-b507-4519-93fd-2a06d5965c79)
![api](https://github.com/comfazil/PowerOfMath-AWS/assets/101056131/cd098c53-cc1d-4001-947e-95e20376107c)
![amplifier](https://github.com/comfazil/PowerOfMath-AWS/assets/101056131/87a3b26a-8531-4384-896e-ff7227b82d2b)
![1](https://github.com/comfazil/PowerOfMath-AWS/assets/101056131/1cb5da7e-37b2-41b4-a76a-d04ccdb458e9)



## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.
