{
  "info": {
    "name": "AWS Device Farm API Purchase Offering",
    "_postman_id": "a7966636-c3d1-45fe-a045-f4b81c2e1819",
    "description": "Immediately purchases offerings for an AWS account.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Device Pool",
      "item": [
        {
          "id": "4fa56aca-a30e-4fab-9a73-9640d964a2f1",
          "name": "createDevicePool",
          "request": {
            "url": "http://example.com/api/?Action=CreateDevicePool?description=description&name=name&projectArn=projectArn&rules=rules",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a device pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c615010-2e6d-4717-8e7d-38d1138319e8"
            }
          ]
        },
        {
          "id": "1f886a89-25d3-4210-a0bb-83baa948d21b",
          "name": "deleteDevicePool",
          "request": {
            "url": "http://example.com/api/?Action=DeleteDevicePool?arn=arn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a device pool given the pool ARN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6dd5786b-19f6-493a-8c96-ea0a1529f19a"
            }
          ]
        },
        {
          "id": "672f85c6-0553-4dd0-aad1-a53b4da07af1",
          "name": "getDevicePool",
          "request": {
            "url": "http://example.com/api/?Action=GetDevicePool?arn=arn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about a device pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9537a2b-e50d-4483-bf63-aa2eb76c206f"
            }
          ]
        },
        {
          "id": "9f7a3404-c8c6-41f2-bb0f-ba427ebe40a1",
          "name": "getDevicePoolCompatibility",
          "request": {
            "url": "http://example.com/api/?Action=GetDevicePoolCompatibility?appArn=appArn&devicePoolArn=devicePoolArn&testType=testType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about compatibility with a device pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d89db20a-249b-420b-9799-0f14b87bc2dd"
            }
          ]
        },
        {
          "id": "602c88d7-1838-4872-9df6-952dc7e634b1",
          "name": "listDevicePools",
          "request": {
            "url": "http://example.com/api/?Action=ListDevicePools?arn=arn&nextToken=nextToken&type=type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about device pools."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "43b82fb9-271c-4666-9335-3439d8bbd679"
            }
          ]
        }
      ]
    },
    {
      "name": "Project",
      "item": [
        {
          "id": "5201cc63-e19f-497b-b827-dbdc8c4dae08",
          "name": "createProject",
          "request": {
            "url": "http://example.com/api/?Action=CreateProject?name=name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3f0b6ec-8cd3-4d38-ade3-65d5f1aadf2d"
            }
          ]
        }
      ]
    },
    {
      "name": "Remote Access Sessions",
      "item": [
        {
          "id": "ae2ea99f-f0c7-4662-a331-3f54f866eda1",
          "name": "createRemoteAccessSession",
          "request": {
            "url": "http://example.com/api/?Action=CreateRemoteAccessSession?configuration=configuration&deviceArn=deviceArn&name=name&projectArn=projectArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Specifies and starts a remote access session."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f43ba8f8-44a0-4cad-aabe-76f0b0c1d541"
            }
          ]
        },
        {
          "id": "da40186d-fcf4-4a2c-80cd-4d9ddc38bbb5",
          "name": "deleteRemoteAccessSession",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRemoteAccessSession?arn=arn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a completed remote access session and its results."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4c11d87e-ecdc-4027-b544-c677942c71ed"
            }
          ]
        },
        {
          "id": "8327e7f3-e59c-42d4-b0d7-18b52ecab11f",
          "name": "getRemoteAccessSession",
          "request": {
            "url": "http://example.com/api/?Action=GetRemoteAccessSession?arn=arn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a link to a currently running remote access session."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9c82e900-8d41-4a34-9878-db23c7da7468"
            }
          ]
        },
        {
          "id": "a5d9956d-e009-42f7-a262-8e02355ae604",
          "name": "installToRemoteAccessSession",
          "request": {
            "url": "http://example.com/api/?Action=InstallToRemoteAccessSession?appArn=appArn&remoteAccessSessionArn=remoteAccessSessionArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Installs an application to the device in a remote access session."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "49698d37-5b7e-48b4-bf21-d5a8e4d19147"
            }
          ]
        },
        {
          "id": "91247ae7-79e8-4f03-913f-5b5b85a6348d",
          "name": "listRemoteAccessSessions",
          "request": {
            "url": "http://example.com/api/?Action=ListRemoteAccessSessions?arn=arn&nextToken=nextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of all currently running remote access sessions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "63cd71da-eca6-4712-b7e0-1afedbd5f184"
            }
          ]
        }
      ]
    },
    {
      "name": "Upload",
      "item": [
        {
          "id": "e7925fc0-a7ca-4187-9cc5-47f20758b9fe",
          "name": "createUpload",
          "request": {
            "url": "http://example.com/api/?Action=CreateUpload?contentType=contentType&name=name&projectArn=projectArn&type=type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Uploads an app or test scripts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0799cb60-865a-471f-85bc-adc90b78e430"
            }
          ]
        },
        {
          "id": "17a53a92-861b-4a9a-8dd5-3b89e58e2d0e",
          "name": "getUpload",
          "request": {
            "url": "http://example.com/api/?Action=GetUpload?arn=arn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about an upload."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e29ca5ce-8674-4903-bfc3-819fe4d22c1c"
            }
          ]
        }
      ]
    },
    {
      "name": "Projects",
      "item": [
        {
          "id": "38d648fa-0703-45d0-a315-8178d88ea2f5",
          "name": "deleteProject",
          "request": {
            "url": "http://example.com/api/?Action=DeleteProject?arn=arn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an AWS Device Farm project, given the project ARN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d3149136-a585-48df-9c40-6addcf27b0c1"
            }
          ]
        },
        {
          "id": "9e819eae-0f9d-4c11-a741-6535fbfc0755",
          "name": "getProject",
          "request": {
            "url": "http://example.com/api/?Action=GetProject?arn=arn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about a project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae02c67c-23bf-486e-ab2d-5cba2eae8c2e"
            }
          ]
        },
        {
          "id": "1567e4cb-37a2-4b92-b2d0-9e87e49ab5f8",
          "name": "listProjects",
          "request": {
            "url": "http://example.com/api/?Action=ListProjects?arn=arn&nextToken=nextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about projects."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f383b7d7-b5e0-41c9-8c9d-7d567019b42a"
            }
          ]
        }
      ]
    },
    {
      "name": "Runs",
      "item": [
        {
          "id": "9253d2d0-77b5-417e-b4d9-26eb3a412f10",
          "name": "deleteRun",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRun?arn=arn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the run, given the run ARN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "80d6822f-a9f3-47c9-abb1-763a0c0a7aa8"
            }
          ]
        },
        {
          "id": "2917f992-156d-45a5-9829-af157fdb1842",
          "name": "getRun",
          "request": {
            "url": "http://example.com/api/?Action=GetRun?arn=arn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about a run."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "795311ed-c946-4a9f-a053-ed500ddf238f"
            }
          ]
        },
        {
          "id": "4071b435-73cc-4777-bba3-6029876361ff",
          "name": "listRuns",
          "request": {
            "url": "http://example.com/api/?Action=ListRuns?arn=arn&nextToken=nextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about runs, given an AWS Device Farm project ARN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d92514a-8327-4524-b2de-970916d4956d"
            }
          ]
        }
      ]
    },
    {
      "name": "Uploads",
      "item": [
        {
          "id": "bc0ecff4-2b03-44de-9044-eaa36e1e93ec",
          "name": "deleteUpload",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUpload?arn=arn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an upload given the upload ARN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0474995a-c45a-4597-9678-fc6aafe0d55b"
            }
          ]
        },
        {
          "id": "019a4d2b-2e79-47bd-a029-a605d44b3498",
          "name": "listUploads",
          "request": {
            "url": "http://example.com/api/?Action=ListUploads?arn=arn&nextToken=nextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about uploads, given an AWS Device Farm project ARN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "634d902c-e0de-4842-a55d-da5def036e4b"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Settings",
      "item": [
        {
          "id": "e0b87a39-2c79-4648-b050-9c86b334d10d",
          "name": "getAccountSettings",
          "request": {
            "url": "http://example.com/api/?Action=GetAccountSettings?accountSettings=accountSettings",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the number of unmetered iOS and/or unmetered Android devices that have been purchased by the account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab36480a-a742-4410-abe2-4bb17f77ff49"
            }
          ]
        }
      ]
    },
    {
      "name": "Devices",
      "item": [
        {
          "id": "4495c818-f8a0-48ac-b47d-6d1eca5f6b35",
          "name": "getDevice",
          "request": {
            "url": "http://example.com/api/?Action=GetDevice?arn=arn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about a unique device type."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a12ce24-a5c8-4f95-8ade-9e83c9f3e651"
            }
          ]
        },
        {
          "id": "43c0dc9a-90ee-4325-af60-816ee28cb44b",
          "name": "listDevices",
          "request": {
            "url": "http://example.com/api/?Action=ListDevices?arn=arn&nextToken=nextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about unique device types."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f1b0520a-ddce-4763-96f2-ebd7142d859e"
            }
          ]
        }
      ]
    },
    {
      "name": "Jobs",
      "item": [
        {
          "id": "fab45ee9-61ed-4f60-8c66-cd28a5c8d662",
          "name": "getJob",
          "request": {
            "url": "http://example.com/api/?Action=GetJob?arn=arn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about a job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "20ae7c56-f8bd-4dc0-af62-bf5e2fa3c820"
            }
          ]
        },
        {
          "id": "47c3fae2-95da-4361-ad29-61e9bddbcfbc",
          "name": "listJobs",
          "request": {
            "url": "http://example.com/api/?Action=ListJobs?arn=arn&nextToken=nextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about jobs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "556c9dd7-0324-4d27-acc8-0e83f369822c"
            }
          ]
        }
      ]
    },
    {
      "name": "Offering Status",
      "item": [
        {
          "id": "b719b5d8-8264-4898-927e-57b3b2b9b85e",
          "name": "getOfferingStatus",
          "request": {
            "url": "http://example.com/api/?Action=GetOfferingStatus?nextToken=nextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the current status and future status of all offerings purchased by an AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1a4fb93-6f19-456a-bd59-2e7c68c53baa"
            }
          ]
        }
      ]
    },
    {
      "name": "Suites",
      "item": [
        {
          "id": "4619c228-a206-4291-a808-c563d654f83f",
          "name": "getSuite",
          "request": {
            "url": "http://example.com/api/?Action=GetSuite?arn=arn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about a suite."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a1adefa1-bcdb-48ff-b6d8-e3a6b883b681"
            }
          ]
        },
        {
          "id": "a82491c1-ca81-40f0-a19e-f86c31e6ba51",
          "name": "listSuites",
          "request": {
            "url": "http://example.com/api/?Action=ListSuites?arn=arn&nextToken=nextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about suites."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9f82b95-c537-415f-864d-c87b02655703"
            }
          ]
        }
      ]
    },
    {
      "name": "Tests",
      "item": [
        {
          "id": "d04626e7-a4f5-4893-9ff3-1b830783d878",
          "name": "getTest",
          "request": {
            "url": "http://example.com/api/?Action=GetTest?arn=arn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about a test."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96bf0583-d57f-471a-9da8-89cb55771a0c"
            }
          ]
        },
        {
          "id": "ffe24da2-641a-400c-9e54-baba489836fd",
          "name": "listTests",
          "request": {
            "url": "http://example.com/api/?Action=ListTests?arn=arn&nextToken=nextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about tests."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ab25989-61eb-478d-949d-f7a468cb5564"
            }
          ]
        }
      ]
    },
    {
      "name": "Artifacts",
      "item": [
        {
          "id": "ac326c47-ef64-4277-9c0e-0e57d6194cb8",
          "name": "listArtifacts",
          "request": {
            "url": "http://example.com/api/?Action=ListArtifacts?arn=arn&nextToken=nextToken&type=type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about artifacts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3eb37284-862e-4a24-8881-1ba972417411"
            }
          ]
        }
      ]
    },
    {
      "name": "Offerings",
      "item": [
        {
          "id": "16cec403-71ba-4921-8055-cdfc9e35c1d1",
          "name": "listOfferings",
          "request": {
            "url": "http://example.com/api/?Action=ListOfferings?nextToken=nextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of products or offerings that the user can manage through the API."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3820e17-2071-49ab-b199-ba49df310dd7"
            }
          ]
        },
        {
          "id": "78eef1ca-7be4-4650-be19-85a1ce86a27c",
          "name": "purchaseOffering",
          "request": {
            "url": "http://example.com/api/?Action=PurchaseOffering?offeringId=offeringId&quantity=quantity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Immediately purchases offerings for an AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9684ccc1-1720-487e-8889-e8f39427c79d"
            }
          ]
        }
      ]
    },
    {
      "name": "Offering Transactions",
      "item": [
        {
          "id": "c66c837a-f723-480d-bc80-c92f4ad41f44",
          "name": "listOfferingTransactions",
          "request": {
            "url": "http://example.com/api/?Action=ListOfferingTransactions?nextToken=nextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of all historical purchases, renewals, and system renewal transactions for an\n      AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4da1cb39-ee99-40b4-98ef-e0679ef26ec6"
            }
          ]
        }
      ]
    },
    {
      "name": "Samples",
      "item": [
        {
          "id": "f2c8381f-5a29-4802-ba75-395ccf09be28",
          "name": "listSamples",
          "request": {
            "url": "http://example.com/api/?Action=ListSamples?arn=arn&nextToken=nextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about samples, given an AWS Device Farm project ARN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9511aa2f-1e41-497b-b7ee-b448856a006a"
            }
          ]
        }
      ]
    },
    {
      "name": "Unique Problems",
      "item": [
        {
          "id": "f90db8df-e3de-4dd5-8c5f-569e940c0936",
          "name": "listUniqueProblems",
          "request": {
            "url": "http://example.com/api/?Action=ListUniqueProblems?arn=arn&nextToken=nextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about unique problems."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a141566-88c5-482a-9ec7-ed4e8ef1337e"
            }
          ]
        }
      ]
    }
  ]
}