# Create-a-mock-stub-service-using-AWS-Lambda

Requirement: Client has asked us to stubs/mock an API service with request & response, so that when that lambda is triggered a response is given, the response has a dynamic time and state and customer ID, which depends on request.

Steps :

Step 1: Create a Lambda Function that returns a hardcoded or dynamic response back to the Client.
Step 2: Setup a Get API, which will forward requests to the Lambda Function 
Step 3 : Invoke the Get API from Postman or Browser
Step 4: Verify the Logs from Cloudwatch


Uploads:

1. The Request response of the API calls ( CreateDelivery_DD.txt & EstimateApi_DD.txt)
2. The JS Files of the Stubbed Lambdas (index.js files in CreateDelivery,Estimate & lambda_function.py in TransactionProcessor)
3. YAML Files of the stubbed Lamdas
4. Instructions Word FILE


