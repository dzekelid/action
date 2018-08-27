{
  "info": {
    "name": "AWS Lambda API Invoke Async",
    "_postman_id": "aac8bc23-6513-4853-870e-6395500c6fd3",
    "description": "ImportantThis API is deprecated.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Permissions",
      "item": [
        {
          "id": "6f5985a5-a1ee-4536-bdd0-c6dcc7d57a66",
          "name": "addPermission",
          "request": {
            "url": "http://example.com/api/?Action=AddPermission?FunctionName=FunctionName&Qualifier=Qualifier",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds a permission to the resource policy associated with the specified AWS Lambda function."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f03bf76c-fd0a-4d96-b4f6-3676ce4e93e6"
            }
          ]
        }
      ]
    },
    {
      "name": "Aliases",
      "item": [
        {
          "id": "6d80f810-131a-44e9-a3d9-a1e1a31acc0c",
          "name": "createAlias",
          "request": {
            "url": "http://example.com/api/?Action=CreateAlias?FunctionName=FunctionName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an alias that points to the specified Lambda function version."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c7944a96-207a-4801-b31e-b7f9f0896443"
            }
          ]
        },
        {
          "id": "7c29cdf2-5d5a-4398-9642-0f258264bd80",
          "name": "deleteAlias",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAlias?FunctionName=FunctionName&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified Lambda function alias."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3839612b-7062-4add-b073-6bb4c680f963"
            }
          ]
        },
        {
          "id": "ccb17300-8d98-4469-9f25-ceb1fa0e74a3",
          "name": "getAlias",
          "request": {
            "url": "http://example.com/api/?Action=GetAlias?FunctionName=FunctionName&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the specified alias information such as the alias ARN, description, and function version it \n      is pointing to."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "66a37208-5c8e-4072-bd9d-a656e580f952"
            }
          ]
        }
      ]
    },
    {
      "name": "Event Sources",
      "item": [
        {
          "id": "0ca58083-e15a-4f1d-a7d6-04d7adfa421d",
          "name": "createEventSourceMapping",
          "request": {
            "url": "http://example.com/api/?Action=CreateEventSourceMapping?BatchSize=BatchSize&Enabled=Enabled&EventSourceArn=EventSourceArn&FunctionName=FunctionName&StartingPosition=StartingPosition&StartingPositionTimestamp=StartingPositionTimestamp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Identifies a stream as an event source for a Lambda function."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3a42837-d041-419f-9029-1a9a787d7f02"
            }
          ]
        },
        {
          "id": "ef891442-143c-4788-93a2-8bbe0993d9e7",
          "name": "deleteEventSourceMapping",
          "request": {
            "url": "http://example.com/api/?Action=DeleteEventSourceMapping?UUID=UUID",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes an event source mapping."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c431e7c3-c9e7-4cf7-aacf-05fc6cde02fb"
            }
          ]
        },
        {
          "id": "d64244d5-e187-4443-abba-cc02d9befaea",
          "name": "getEventSourceMapping",
          "request": {
            "url": "http://example.com/api/?Action=GetEventSourceMapping?UUID=UUID",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns configuration information for the specified event source mapping (see."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8ded3fcb-237d-4924-9406-ac7e6851cb53"
            }
          ]
        }
      ]
    },
    {
      "name": "Functions",
      "item": [
        {
          "id": "6a40cbb6-ad29-4bdc-b933-7047a879f637",
          "name": "createFunction",
          "request": {
            "url": "http://example.com/api/?Action=CreateFunction?Code=Code&DeadLetterConfig=DeadLetterConfig&Description=Description&Environment=Environment&FunctionName=FunctionName&Handler=Handler&KMSKeyArn=KMSKeyArn&MemorySize=MemorySize&Publish=Publish&Role=Role&Runtime=Runtime&Timeout=Timeout&VpcConfig=VpcConfig",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new Lambda function."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6afc5d48-7733-4fa6-a120-22e10b7c7af2"
            }
          ]
        },
        {
          "id": "30586cbd-4fb7-477b-a9df-0f5f1e789674",
          "name": "deleteFunction",
          "request": {
            "url": "http://example.com/api/?Action=DeleteFunction?FunctionName=FunctionName&Qualifier=Qualifier",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified Lambda function code and configuration."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "55b7830f-0001-4940-919f-4c7a68046fc7"
            }
          ]
        },
        {
          "id": "ee9e085b-2cf2-4a3f-bc1b-3e6c3b3b9961",
          "name": "getFunction",
          "request": {
            "url": "http://example.com/api/?Action=GetFunction?FunctionName=FunctionName&Qualifier=Qualifier",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the configuration information of the Lambda function and a presigned URL \n      link to the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b734204-0e4a-4327-ab95-d1170b1451e4"
            }
          ]
        },
        {
          "id": "b59f6c92-ede4-455b-8b3a-ed49e030e50d",
          "name": "getFunctionConfiguration",
          "request": {
            "url": "http://example.com/api/?Action=GetFunctionConfiguration?FunctionName=FunctionName&Qualifier=Qualifier",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the configuration information of the Lambda function."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6961ea07-7d94-47a5-91b8-8fc616223ff1"
            }
          ]
        }
      ]
    },
    {
      "name": "Accounts",
      "item": [
        {
          "id": "9133ce75-7b2d-4289-b321-94ba11b43047",
          "name": "getAccountSettings",
          "request": {
            "url": "http://example.com/api/?Action=GetAccountSettings?AccountLimit=AccountLimit&AccountUsage=AccountUsage",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a customer's account settings."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4e44a7c3-973f-4c8d-b6fe-367f4aaa19fa"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "67ed4b3b-036a-49d0-be43-2379a25763fb",
          "name": "getPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetPolicy?FunctionName=FunctionName&Qualifier=Qualifier",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the resource policy associated with the specified Lambda function."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "325a510b-ed17-4d37-bbe4-f1fa6d783037"
            }
          ]
        }
      ]
    },
    {
      "name": "Invoke",
      "item": [
        {
          "id": "e345bad5-7eae-4ad0-9e1c-f6d6b13abf96",
          "name": "invoke",
          "request": {
            "url": "http://example.com/api/?Action=Invoke?ClientContext=ClientContext&FunctionName=FunctionName&InvocationType=InvocationType&LogType=LogType&Qualifier=Qualifier",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Invokes a specific Lambda function."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4532e4b3-e1da-4a27-8dcf-0a8e1f9a4ff3"
            }
          ]
        }
      ]
    },
    {
      "name": "Async",
      "item": [
        {
          "id": "927b800c-58f4-4fd5-a646-54a5e090a763",
          "name": "invokeAsync",
          "request": {
            "url": "http://example.com/api/?Action=InvokeAsync?FunctionName=FunctionName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "ImportantThis API is deprecated."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04e2bc9c-d8cd-4346-b9ff-fc8f5c2784a7"
            }
          ]
        }
      ]
    }
  ]
}