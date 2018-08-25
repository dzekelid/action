{
  "info": {
    "name": "AWS WAF API Create Byte Match Set",
    "_postman_id": "d1835b4b-ba54-4caf-b4f8-8ff47276641d",
    "description": "Service: AWS WAFCreates a ByteMatchSet.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Web ACL",
      "item": [
        {
          "id": "375e2c65-57b3-43c2-9dbc-8be7410bf1e6",
          "name": "associateWebACL",
          "request": {
            "url": "http://example.com/api/?Action=AssociateWebACL?ResourceArn=ResourceArn&WebACLId=WebACLId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAF RegionalAssociates a web ACL with a resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8388e9d8-8959-425e-9e11-5796b02ec586"
            }
          ]
        }
      ]
    },
    {
      "name": "Byte Match Set",
      "item": [
        {
          "id": "88fc1e7d-ec72-444d-8846-7b6e3a137715",
          "name": "createByteMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateByteMatchSet?ChangeToken=ChangeToken&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates a ByteMatchSet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e2793c87-ad93-4682-8856-2c513d6ba750"
            }
          ]
        }
      ]
    }
  ]
}