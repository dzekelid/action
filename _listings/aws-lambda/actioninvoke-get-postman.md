{
  "info": {
    "name": "AWS Lambda API Invoke",
    "_postman_id": "df007f29-b749-42eb-a4c5-2bbf88c61744",
    "description": "Invokes a specific Lambda function.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Permissions",
      "item": [
        {
          "id": "eea73959-0c60-4d9d-895c-dca865533cf5",
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
              "id": "cd6a5c5f-d32b-4e65-8822-e50b29f1595d"
            }
          ]
        }
      ]
    },
    {
      "name": "Aliases",
      "item": [
        {
          "id": "43990dd3-8fe7-48c7-b4c8-c2c7a3108ccd",
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
              "id": "277f9a26-dfa4-4df8-a2cd-ec37d3ab565a"
            }
          ]
        },
        {
          "id": "727d0452-14e9-4941-8e1e-f76234f7c222",
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
              "id": "93af2f85-545d-49da-9426-da171aebafbf"
            }
          ]
        },
        {
          "id": "6498938c-3514-4175-ae52-5cc3316091d8",
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
              "id": "daefb5d3-8594-4146-8429-6b3c5abaa7df"
            }
          ]
        }
      ]
    },
    {
      "name": "Event Sources",
      "item": [
        {
          "id": "48d2a8c0-678a-4142-bc0d-92cdfbf48dee",
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
              "id": "fde09b61-9d8d-4044-8066-0c4891c851c2"
            }
          ]
        },
        {
          "id": "cac4bdd2-414c-4657-9a21-67e560911594",
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
              "id": "a96b1165-128d-42ef-9016-d3eaaf5c604c"
            }
          ]
        },
        {
          "id": "bb303d68-e537-4998-89b8-ec224814ee38",
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
              "id": "61940481-c87e-4259-9239-86bfccf20d8f"
            }
          ]
        }
      ]
    },
    {
      "name": "Functions",
      "item": [
        {
          "id": "e27d1ec8-b7f8-4895-a858-907c9093ca3e",
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
              "id": "c0801694-5732-4d45-bab9-1bc0511599c8"
            }
          ]
        },
        {
          "id": "f59274b3-54c8-4248-a045-bcfa5830bc47",
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
              "id": "2b90f576-4acb-497d-8cd4-6f74d59060e3"
            }
          ]
        },
        {
          "id": "3b4400b3-fc2b-43ed-b3f6-2911fd17a7b6",
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
              "id": "777a58b3-7dff-4528-8d54-fc9626997d8a"
            }
          ]
        },
        {
          "id": "b55ff733-5fd5-41f8-a604-39b024cdab38",
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
              "id": "a0e2aeed-1591-4824-96fc-9397bfe00391"
            }
          ]
        }
      ]
    },
    {
      "name": "Accounts",
      "item": [
        {
          "id": "799f21a4-3b64-40bc-8965-3451771c10e6",
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
              "id": "9ed68efc-ab2c-4f05-be0a-385bead681f8"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "e166a417-e155-40cf-af2c-096705bb25ab",
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
              "id": "fc0a277e-7d31-4389-8228-b42d65ff0205"
            }
          ]
        }
      ]
    },
    {
      "name": "Invoke",
      "item": [
        {
          "id": "79b9a12f-bf3f-4f24-af13-feac2e7428fa",
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
              "id": "10ca1e6a-71b0-4570-ac26-23b4ee53acb7"
            }
          ]
        }
      ]
    }
  ]
}