{
  "info": {
    "name": "AWS WAF API Update IP Set",
    "_postman_id": "1b7df094-602a-4025-917d-94bcce1f485a",
    "description": "Service: AWS WAFInserts or deletes.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Web ACL",
      "item": [
        {
          "id": "6f8d7530-99df-42c9-a13a-5950135e73b1",
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
              "id": "45fbdd09-9476-43c9-ac56-7e0f8e1672c5"
            }
          ]
        },
        {
          "id": "3f708c1d-0424-490f-ba30-ac4f9d5fd361",
          "name": "createWebACL",
          "request": {
            "url": "http://example.com/api/?Action=CreateWebACL?ChangeToken=ChangeToken&DefaultAction=DefaultAction&MetricName=MetricName&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates a WebACL, which contains the Rules that identify the CloudFront web requests that you want to allow, block, or count."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eea40788-a1ad-4d36-b9bf-75d5a78f1c49"
            }
          ]
        },
        {
          "id": "05aea6f8-c132-4009-a18b-b1f122c6a496",
          "name": "deleteWebACL",
          "request": {
            "url": "http://example.com/api/?Action=DeleteWebACL?ChangeToken=ChangeToken&WebACLId=WebACLId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f2f9004-11e8-4f3d-8db2-1c02580915a0"
            }
          ]
        },
        {
          "id": "e64ad23b-e249-4655-b030-566716f053a5",
          "name": "disassociateWebACL",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateWebACL?ResourceArn=ResourceArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAF RegionalRemoves a web ACL from the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c5c05b6-5fbb-4243-99ce-a8fdb167c5f2"
            }
          ]
        },
        {
          "id": "fdb33cf3-63e2-4e1e-8483-1d152c42da22",
          "name": "getWebACL",
          "request": {
            "url": "http://example.com/api/?Action=GetWebACL?WebACLId=WebACLId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c4593d1b-1bb4-4c42-832f-863ce53a1ba2"
            }
          ]
        },
        {
          "id": "bd79a1d1-3e41-4441-853d-047e0b53081e",
          "name": "getWebACLForResource",
          "request": {
            "url": "http://example.com/api/?Action=GetWebACLForResource?ResourceArn=ResourceArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAF RegionalReturns the web ACL for the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5f36eb7b-7902-44c5-a463-f22d58cf501f"
            }
          ]
        },
        {
          "id": "43c0c90b-bab0-4ba2-828d-a57ca8d4f0bc",
          "name": "listResourcesForWebACL",
          "request": {
            "url": "http://example.com/api/?Action=ListResourcesForWebACL?WebACLId=WebACLId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAF RegionalReturns an array of resources associated with the specified web ACL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "117318f8-ce64-4a6d-bf74-0733a4ce8249"
            }
          ]
        },
        {
          "id": "18153cb3-39c7-49a0-973f-1b8dd53e7198",
          "name": "listWebACLs",
          "request": {
            "url": "http://example.com/api/?Action=ListWebACLs?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8caa1773-0a15-494e-874e-a6dc41d05ff2"
            }
          ]
        }
      ]
    },
    {
      "name": "Byte Match Set",
      "item": [
        {
          "id": "03a8ed4e-d16d-4f22-b8b2-c6b59a66b673",
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
              "id": "25703f6d-033d-4ffd-9fac-ee31b926e143"
            }
          ]
        },
        {
          "id": "4ea73283-5899-4408-a03d-bdfdd01b979d",
          "name": "deleteByteMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteByteMatchSet?ByteMatchSetId=ByteMatchSetId&ChangeToken=ChangeToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1969c168-0861-4aec-9dcc-c1ca053604cc"
            }
          ]
        },
        {
          "id": "49348db5-96eb-43ec-8327-d405ef7ed2a1",
          "name": "getByteMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=GetByteMatchSet?ByteMatchSetId=ByteMatchSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3a6916d-bab9-44e3-b91a-f5c0078557f7"
            }
          ]
        },
        {
          "id": "23f5aa94-05ca-464f-a9cc-30609369def5",
          "name": "updateByteMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=UpdateByteMatchSet?ByteMatchSetId=ByteMatchSetId&ChangeToken=ChangeToken&Updates=Updates",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFInserts or deletes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af8f2aa5-d9f5-4976-ac65-5f01f26b99d8"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Sets",
      "item": [
        {
          "id": "4ab4ffd8-57a8-421a-89b0-f5539dfb98a7",
          "name": "createIPSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateIPSet?ChangeToken=ChangeToken&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates an."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "42c42411-756c-4d09-b199-f3d1a11567c5"
            }
          ]
        },
        {
          "id": "80107dca-7cdf-460c-87d7-497616596ee8",
          "name": "deleteIPSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIPSet?ChangeToken=ChangeToken&IPSetId=IPSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes an."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "666212e3-8724-42a5-850c-5ac8b35e04d9"
            }
          ]
        },
        {
          "id": "15393daf-5359-4579-a9d6-8b1034624dfb",
          "name": "getIPSet",
          "request": {
            "url": "http://example.com/api/?Action=GetIPSet?IPSetId=IPSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "62b3c9e4-e202-458f-86d9-6a38eba951a5"
            }
          ]
        },
        {
          "id": "f2dc5629-dcc3-4fcd-a61a-f72f4a680a47",
          "name": "listIPSets",
          "request": {
            "url": "http://example.com/api/?Action=ListIPSets?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c600223-71ef-4221-a357-2572734c16fe"
            }
          ]
        },
        {
          "id": "aceff68c-52b5-486a-970d-f788f74bb3ed",
          "name": "updateIPSet",
          "request": {
            "url": "http://example.com/api/?Action=UpdateIPSet?ChangeToken=ChangeToken&IPSetId=IPSetId&Updates=Updates",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFInserts or deletes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd60af78-23ba-4571-9d45-fe05ccdcdd46"
            }
          ]
        }
      ]
    },
    {
      "name": "Rules",
      "item": [
        {
          "id": "c2666d57-2695-45af-8730-238a87ea4155",
          "name": "createRule",
          "request": {
            "url": "http://example.com/api/?Action=CreateRule?ChangeToken=ChangeToken&MetricName=MetricName&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates a Rule, which contains the IPSet objects, ByteMatchSet objects, and \n\t\t\tother predicates that identify the requests that you want to block."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0facd082-ee48-4ea0-afa7-879ddbf409c1"
            }
          ]
        },
        {
          "id": "0c59aa2b-e31b-43c2-ac2d-fa36b1cda405",
          "name": "deleteRule",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRule?ChangeToken=ChangeToken&RuleId=RuleId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bc27bd81-0b6c-4690-80cc-275f3a9d1c48"
            }
          ]
        },
        {
          "id": "3a0369a2-6b6d-4be3-85a8-6f74dae4676f",
          "name": "getRule",
          "request": {
            "url": "http://example.com/api/?Action=GetRule?RuleId=RuleId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8ead558c-6176-4c9c-8eb8-4b21b04cfdc8"
            }
          ]
        },
        {
          "id": "d2395766-06f7-4ee9-b200-b672a07bf25d",
          "name": "listRules",
          "request": {
            "url": "http://example.com/api/?Action=ListRules?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7b2d409b-8428-4ef6-bb6e-014e9716e676"
            }
          ]
        }
      ]
    },
    {
      "name": "Size Constraint Set",
      "item": [
        {
          "id": "fc31bed5-41f4-408e-ab85-3008c8b283d0",
          "name": "createSizeConstraintSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateSizeConstraintSet?ChangeToken=ChangeToken&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates a SizeConstraintSet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04e340cf-1079-4b37-9f0f-905c45387e9f"
            }
          ]
        },
        {
          "id": "d7fe3e1e-fd1c-498d-944e-66080689b471",
          "name": "deleteSizeConstraintSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSizeConstraintSet?ChangeToken=ChangeToken&SizeConstraintSetId=SizeConstraintSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fddbd9ef-0d8a-4b13-b996-5ad877d7660a"
            }
          ]
        },
        {
          "id": "9b2b6122-ca7b-4326-b54f-2038dbe56392",
          "name": "getSizeConstraintSet",
          "request": {
            "url": "http://example.com/api/?Action=GetSizeConstraintSet?SizeConstraintSetId=SizeConstraintSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "799d0d24-1b67-434a-9c0f-c98e871ed60e"
            }
          ]
        }
      ]
    },
    {
      "name": "SQL Injection Match Set",
      "item": [
        {
          "id": "8326461d-1bf8-42ab-a3d5-eccf4f2f9502",
          "name": "createSqlInjectionMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateSqlInjectionMatchSet?ChangeToken=ChangeToken&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ace7f599-2f57-4685-ac3f-20b30934c258"
            }
          ]
        },
        {
          "id": "d2535433-e51b-4989-9e16-d09c262fa5b5",
          "name": "deleteSqlInjectionMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSqlInjectionMatchSet?ChangeToken=ChangeToken&SqlInjectionMatchSetId=SqlInjectionMatchSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b7a06f17-9e1b-4e9f-a952-26e48a6db889"
            }
          ]
        },
        {
          "id": "d9c20768-6a36-46f4-8d0e-0709be3ed1a6",
          "name": "getSqlInjectionMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=GetSqlInjectionMatchSet?SqlInjectionMatchSetId=SqlInjectionMatchSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c19f847d-fef0-4600-9406-797198c9798f"
            }
          ]
        }
      ]
    },
    {
      "name": "XSS Match Set",
      "item": [
        {
          "id": "cfaa51fa-e2ce-4ba9-9fb5-a8f0e6930a3e",
          "name": "createXssMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateXssMatchSet?ChangeToken=ChangeToken&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates an."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a97bee55-1c73-410f-bf02-fcdc54305be1"
            }
          ]
        },
        {
          "id": "3a146792-667d-44da-b019-1e31bd0d3ce8",
          "name": "deleteXssMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteXssMatchSet?ChangeToken=ChangeToken&XssMatchSetId=XssMatchSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes an."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5fcefb12-b5f2-45b1-a34f-1e9210a1f7fa"
            }
          ]
        },
        {
          "id": "0e1e4abe-3dba-45c7-b407-9954a5263911",
          "name": "getXssMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=GetXssMatchSet?XssMatchSetId=XssMatchSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "67ca822c-81b3-4283-a7df-42403a0c51ac"
            }
          ]
        },
        {
          "id": "2255f938-211c-4b4a-ac91-2014d9de8d97",
          "name": "listXssMatchSets",
          "request": {
            "url": "http://example.com/api/?Action=ListXssMatchSets?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c62bc650-1b7a-40aa-a26c-f6d265d3741c"
            }
          ]
        }
      ]
    },
    {
      "name": "Change Token",
      "item": [
        {
          "id": "a470d036-53ea-41b6-be30-5ae978a846d7",
          "name": "getChangeToken",
          "request": {
            "url": "http://example.com/api/?Action=GetChangeToken?ChangeToken=ChangeToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFWhen you want to create, update, or delete AWS WAF objects, get a change token and include the change token in the create, update, or delete request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5040b1e6-6595-4ace-827c-a379b0a80fe7"
            }
          ]
        },
        {
          "id": "52f42046-a56d-4cba-be6f-292f304dfa0f",
          "name": "getChangeTokenStatus",
          "request": {
            "url": "http://example.com/api/?Action=GetChangeTokenStatus?ChangeToken=ChangeToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the status of a ChangeToken that you got by calling."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "705961d8-d377-496c-b350-7252c57e949e"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "6a7a3d6e-b400-426d-af6f-d3912ced2756",
          "name": "getSampledRequests",
          "request": {
            "url": "http://example.com/api/?Action=GetSampledRequests?MaxItems=MaxItems&RuleId=RuleId&TimeWindow=TimeWindow&WebAclId=WebAclId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFGets detailed information about a specified number of requests--a sample--that AWS WAF randomly selects from among the first 5,000 requests that your AWS resource received during a time range that you choose."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1fed984a-f0d8-47a0-887b-356729b9ae4d"
            }
          ]
        }
      ]
    },
    {
      "name": "Byte Match Sets",
      "item": [
        {
          "id": "b8597d84-38c2-4420-8b54-c07fba53f04b",
          "name": "listByteMatchSets",
          "request": {
            "url": "http://example.com/api/?Action=ListByteMatchSets?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1bfd4162-b63b-4ffb-b097-07e20c5a6a1a"
            }
          ]
        }
      ]
    },
    {
      "name": "Size Constraint Sets",
      "item": [
        {
          "id": "9026252b-f949-44c2-aa8e-226a851b63bf",
          "name": "listSizeConstraintSets",
          "request": {
            "url": "http://example.com/api/?Action=ListSizeConstraintSets?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "068acbab-09bd-4b15-a84f-3df64277b844"
            }
          ]
        }
      ]
    },
    {
      "name": "SQL Injection Match Sets",
      "item": [
        {
          "id": "7af71e9d-5929-4d33-939d-ba37bb61618f",
          "name": "listSqlInjectionMatchSets",
          "request": {
            "url": "http://example.com/api/?Action=ListSqlInjectionMatchSets?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ee39e29-3e57-4058-9020-34b563f8b900"
            }
          ]
        }
      ]
    }
  ]
}