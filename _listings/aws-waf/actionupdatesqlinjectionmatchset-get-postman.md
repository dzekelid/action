{
  "info": {
    "name": "AWS WAF API Update SQL Injection Match Set",
    "_postman_id": "e33de4fe-0316-41de-a8e7-131012fb2fae",
    "description": "Service: AWS WAFInserts or deletes.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Web ACL",
      "item": [
        {
          "id": "e6b37592-a252-4a53-b76a-021695007ec1",
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
              "id": "ae3a4920-18a7-4b56-b616-5b91a2ba54ec"
            }
          ]
        },
        {
          "id": "4967a8cc-a440-491b-85fd-c611f7ac2c7e",
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
              "id": "e94ddb5d-3b93-41e2-983b-1b7998fad686"
            }
          ]
        },
        {
          "id": "4acd5f44-571f-4429-b26b-bd445a57166c",
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
              "id": "60468090-1b59-4515-86bd-f3830e8276d9"
            }
          ]
        },
        {
          "id": "00bf38fa-67ac-4bb4-8728-03064c4394e8",
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
              "id": "5f55ead9-af14-4e65-adaa-1cedb41b7fb1"
            }
          ]
        },
        {
          "id": "b6d3fd7c-434b-4bf3-ba3c-3b5ab19514ed",
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
              "id": "be876fa2-c4c0-4706-9f3c-72dce912f965"
            }
          ]
        },
        {
          "id": "006c4755-8b29-4b4c-bef9-aa3162d59005",
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
              "id": "092936a2-5e8a-4c99-a125-58c5bbd6cd17"
            }
          ]
        },
        {
          "id": "17b8f1af-e539-4aea-9c44-f55360feb07e",
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
              "id": "0c421848-5d1e-4db9-8391-51a7e89579fc"
            }
          ]
        },
        {
          "id": "95c41250-1af1-4fa1-bf16-41441ac40a85",
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
              "id": "570f42f5-c758-4edd-80f5-ef5085e8fbc5"
            }
          ]
        }
      ]
    },
    {
      "name": "Byte Match Set",
      "item": [
        {
          "id": "3a6e2246-e521-4fa1-a387-bc18c2673ad0",
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
              "id": "1eacc725-522d-41c0-9eec-975d0a1aa1b6"
            }
          ]
        },
        {
          "id": "ab2800ce-e3ea-484f-9814-5aee6cd3e725",
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
              "id": "de9d1870-45d4-46b1-8554-bbd7de65bf10"
            }
          ]
        },
        {
          "id": "7bdb2ab8-a044-4dfd-81e3-c51581803a02",
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
              "id": "b434991a-4641-4c1f-b821-f1fb14d502cd"
            }
          ]
        },
        {
          "id": "1d532a28-2314-42aa-9e18-dffefe51483e",
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
              "id": "27178117-4f2f-4b4c-9aa3-54048936ac6c"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Sets",
      "item": [
        {
          "id": "baed6f0e-671c-4cbe-98c0-596238c3b3bd",
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
              "id": "9aca2146-fb1b-4878-985e-92a5e65deed6"
            }
          ]
        },
        {
          "id": "d613093f-1bd1-4147-8694-2f5454ff622a",
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
              "id": "63868512-256b-4f60-bae6-3ea80bc1eeaa"
            }
          ]
        },
        {
          "id": "cca52446-dbb9-48c0-8a38-e5e49bb068b6",
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
              "id": "65a89d72-f02f-4cc6-bbc4-5e203c3215d6"
            }
          ]
        },
        {
          "id": "80bc1ebd-1ee3-4dad-a9f8-d9e8775f3f13",
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
              "id": "21efba06-a68e-4187-a3a8-794f3f1e25d0"
            }
          ]
        },
        {
          "id": "cb672b69-623e-40c5-964d-82d32dc8a58a",
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
              "id": "1a65519f-13f1-4ff5-9ac6-8b29096bc0f2"
            }
          ]
        }
      ]
    },
    {
      "name": "Rules",
      "item": [
        {
          "id": "861af8ab-31f7-4a4c-b6b9-24314c1395b9",
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
              "id": "9ea1656a-e4f3-4dc6-af87-77f5ef5554dd"
            }
          ]
        },
        {
          "id": "549e9217-9b24-462d-b53a-88594466f915",
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
              "id": "91f38ea8-18e8-47ba-9348-a9b2f0303adc"
            }
          ]
        },
        {
          "id": "4fbb00e8-c2a6-4952-bf77-6401936a4974",
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
              "id": "cf7bb8db-8bbe-40ac-ba1b-4abb94af408f"
            }
          ]
        },
        {
          "id": "81be9a71-4414-4d89-ba6e-2bbb29aaa87c",
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
              "id": "9086ff5f-bd19-4837-952e-f7f68d2581c9"
            }
          ]
        },
        {
          "id": "06bd4e27-6855-4d71-8891-86b335c49343",
          "name": "updateRule",
          "request": {
            "url": "http://example.com/api/?Action=UpdateRule?ChangeToken=ChangeToken&RuleId=RuleId&Updates=Updates",
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
              "id": "8fab3e16-8824-4786-b1d3-fcd78d78677f"
            }
          ]
        }
      ]
    },
    {
      "name": "Size Constraint Set",
      "item": [
        {
          "id": "3c2ec347-6251-489c-aee5-82538d4bd4c7",
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
              "id": "f48d2de1-871f-41ef-8d0f-93648670214c"
            }
          ]
        },
        {
          "id": "2707ef60-16ed-4113-b75f-069be9e9d187",
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
              "id": "da35597f-fa72-4943-a223-96d9c0a4d8b1"
            }
          ]
        },
        {
          "id": "af7e1c97-7b97-4c34-8c5e-8b946275a384",
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
              "id": "a7991c1e-a32d-457a-be18-a17006532791"
            }
          ]
        },
        {
          "id": "8500fca3-1f7b-46b9-9723-47da20ea4b3f",
          "name": "updateSizeConstraintSet",
          "request": {
            "url": "http://example.com/api/?Action=UpdateSizeConstraintSet?ChangeToken=ChangeToken&SizeConstraintSetId=SizeConstraintSetId&Updates=Updates",
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
              "id": "d4e4323d-b4ba-42b5-9a3b-422037ecdbf9"
            }
          ]
        }
      ]
    },
    {
      "name": "SQL Injection Match Set",
      "item": [
        {
          "id": "74f39002-41c2-49ee-8e64-e49f2fa2ce73",
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
              "id": "0ce0aa8f-efd3-43b7-bf43-ef5c4e9f67e8"
            }
          ]
        },
        {
          "id": "aee7a111-1ef8-4d9f-8f9a-557fc3f03d75",
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
              "id": "ea223b64-e0f2-4e83-8465-f71529eb32a2"
            }
          ]
        },
        {
          "id": "933430f7-7a7a-4bad-b5b9-f761c8f86b01",
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
              "id": "48f96be6-b35b-47d9-8b65-b952f29432ce"
            }
          ]
        }
      ]
    },
    {
      "name": "XSS Match Set",
      "item": [
        {
          "id": "a153a672-bfab-4833-bd90-85f319493f58",
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
              "id": "f0edfb8e-b5a7-49f7-af25-f0f05fb6a7e4"
            }
          ]
        },
        {
          "id": "82f97f8c-3e5f-4a2a-9cea-f5fd4203b027",
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
              "id": "5bcc938f-f75e-4e90-a6f1-789949eb89a2"
            }
          ]
        },
        {
          "id": "23482b26-0b51-4510-88ee-489221d88df2",
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
              "id": "98f1fcb5-cfef-4e4e-bf71-62eaf061ba2d"
            }
          ]
        },
        {
          "id": "b8939b5c-e20e-47ca-a6cb-3047dd5666b6",
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
              "id": "562c19ed-ad4f-4a36-ae6a-c0f62695caef"
            }
          ]
        }
      ]
    },
    {
      "name": "Change Token",
      "item": [
        {
          "id": "d1b7fc35-9626-487e-9b72-8d4eafb28ba0",
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
              "id": "4ace0f3e-238f-4f4a-986d-7e947feb9a79"
            }
          ]
        },
        {
          "id": "027d95e8-a8dc-46cf-b2a6-c0fc7fdc1af9",
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
              "id": "cc4f6de9-644e-4518-8271-a2ba1d3f0c53"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "bbdc4873-86e4-457b-b18e-1b1c8d321c06",
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
              "id": "e9774ae9-ba9d-4021-b273-0431c1299348"
            }
          ]
        }
      ]
    },
    {
      "name": "Byte Match Sets",
      "item": [
        {
          "id": "b8f1c0b4-f2a1-45e8-b26e-e78dd89940ec",
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
              "id": "c4636444-10b0-4242-b128-f21ae4eaf5d4"
            }
          ]
        }
      ]
    },
    {
      "name": "Size Constraint Sets",
      "item": [
        {
          "id": "7cc1c66f-c8c7-409d-8906-cf9cd52720d9",
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
              "id": "d6e6c312-eee2-426c-8d13-9c77d2ff8ffc"
            }
          ]
        }
      ]
    },
    {
      "name": "SQL Injection Match Sets",
      "item": [
        {
          "id": "6b60877b-55ad-4a83-b34b-42b8850852b8",
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
              "id": "5a36f565-6222-4ab3-858b-da22b7c40dcf"
            }
          ]
        },
        {
          "id": "a118873d-dcdf-4347-ae29-e2d2b4212cca",
          "name": "updateSqlInjectionMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=UpdateSqlInjectionMatchSet?ChangeToken=ChangeToken&SqlInjectionMatchSetId=SqlInjectionMatchSetId&Updates=Updates",
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
              "id": "69cba3d4-ed4d-429e-b587-645e937792f7"
            }
          ]
        }
      ]
    }
  ]
}