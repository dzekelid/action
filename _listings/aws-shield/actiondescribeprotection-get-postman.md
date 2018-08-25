{
  "info": {
    "name": "AWS Shield API Describe Protection",
    "_postman_id": "a4637822-3b59-4fc0-bbea-620c694871b2",
    "description": "Lists the details of a.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Protection",
      "item": [
        {
          "id": "506f0399-7e84-4fd4-a7d2-bed458438d8a",
          "name": "createProtection",
          "request": {
            "url": "http://example.com/api/?Action=CreateProtection?Name=Name&ResourceArn=ResourceArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables AWS Shield Advanced for a specific AWS resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0214dbc6-faa3-41e8-afcf-76b45ca13ca2"
            }
          ]
        },
        {
          "id": "707ac67e-0833-4f68-8e66-f48bfa9afc5b",
          "name": "createSubscription",
          "request": {
            "url": "http://example.com/api/?Action=CreateSubscription",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Activates AWS Shield Advanced for an account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fef5bff5-852a-42bf-bc63-67cae9cbbd72"
            }
          ]
        },
        {
          "id": "4f588602-8cb8-4a30-92e0-3767fd02c1e6",
          "name": "deleteProtection",
          "request": {
            "url": "http://example.com/api/?Action=DeleteProtection?ProtectionId=ProtectionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an AWS Shield Advanced."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "351ceee6-7ee5-455a-90b0-b01906a0a60d"
            }
          ]
        },
        {
          "id": "66593470-c4f0-460d-ad1b-4d0c3ad46f09",
          "name": "deleteSubscription",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSubscription",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes AWS Shield Advanced from an account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "82e9c19e-4d05-485a-80dd-9c56e8c5c0fc"
            }
          ]
        },
        {
          "id": "6de97eb6-2989-4a18-a519-79546e3d95e7",
          "name": "describeProtection",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProtection?ProtectionId=ProtectionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the details of a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b6c7615-e081-4274-b700-c3e782ccc47c"
            }
          ]
        }
      ]
    },
    {
      "name": "Attacks",
      "item": [
        {
          "id": "e87e14fd-354c-4b30-a759-3754130a06c0",
          "name": "describeAttack",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAttack?AttackId=AttackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the details of a DDoS attack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "978c697e-b12d-4264-bdc4-4fb71823c516"
            }
          ]
        }
      ]
    }
  ]
}