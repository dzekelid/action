{
  "info": {
    "name": "AWS AppStream 2.0 API Delete Stack",
    "_postman_id": "042f63d4-4a08-41f6-b398-56ade5819ce9",
    "description": "Deletes the stack.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Fleet",
      "item": [
        {
          "id": "1f4d11ed-58fb-4d7f-8a9f-73c4144fc75c",
          "name": "AssociateFleet",
          "request": {
            "url": "http://example.com/api/?Action=AssociateFleet?FleetName=FleetName&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associate a fleet to a stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c41d39c-e5b4-4fe0-ac5b-02e52f94d9dd"
            }
          ]
        },
        {
          "id": "f8e47fbc-a16b-4bf3-8bde-640af755f6cb",
          "name": "CreateFleet",
          "request": {
            "url": "http://example.com/api/?Action=CreateFleet?ComputeCapacity=ComputeCapacity&Description=Description&DisconnectTimeoutInSeconds=DisconnectTimeoutInSeconds&DisplayName=DisplayName&ImageName=ImageName&InstanceType=InstanceType&MaxUserDurationInSeconds=MaxUserDurationInSeconds&Name=Name&VpcConfig=VpcConfig",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new fleet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d7fcf0f-3735-40b7-a123-c303bb8d7f32"
            }
          ]
        },
        {
          "id": "755ba17c-4ab6-4fda-9b22-a93be50629b7",
          "name": "CreateStack",
          "request": {
            "url": "http://example.com/api/?Action=CreateStack?Description=Description&DisplayName=DisplayName&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Create a new stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "07473940-bc35-4189-bd12-d4b7a9c46781"
            }
          ]
        },
        {
          "id": "da545ef5-7061-407a-9a32-6fa377b5fa81",
          "name": "DeleteFleet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteFleet?Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a fleet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e8dfab3-f2fb-43e5-93c3-590acc7becc1"
            }
          ]
        }
      ]
    },
    {
      "name": "URL",
      "item": [
        {
          "id": "aec5c0ab-8e70-4e60-add2-a30e3e38d591",
          "name": "CreateStreamingURL",
          "request": {
            "url": "http://example.com/api/?Action=CreateStreamingURL?ApplicationId=ApplicationId&FleetName=FleetName&SessionContext=SessionContext&StackName=StackName&UserId=UserId&Validity=Validity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a URL to start an AppStream 2."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "26b186f0-c4cf-4cb4-bec4-ce1bc86c922e"
            }
          ]
        }
      ]
    },
    {
      "name": "Stack",
      "item": [
        {
          "id": "d45f3ffe-9476-4744-bb74-82e1a4adf0b0",
          "name": "DeleteStack",
          "request": {
            "url": "http://example.com/api/?Action=DeleteStack?Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c4cc8629-fbef-4143-ac3e-ffe115fe564c"
            }
          ]
        }
      ]
    }
  ]
}