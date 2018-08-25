{
  "info": {
    "name": "AWS Device Farm API List Unique Problems",
    "_postman_id": "06e5f838-5c45-494b-aa2e-37f856bbab77",
    "description": "Gets information about unique problems.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Device Pool",
      "item": [
        {
          "id": "5f8ecab6-a0dc-48f5-8c2d-bea4f6edf54b",
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
              "id": "f3c317f3-0045-44d1-866f-5baf38a90d5e"
            }
          ]
        },
        {
          "id": "b4a8fa73-0bbf-4dc7-acda-7df54ba5b95a",
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
              "id": "7cc1676f-bc09-42df-90a7-53326a298503"
            }
          ]
        },
        {
          "id": "12884414-8d36-40aa-80dd-9d0cda407292",
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
              "id": "6fe42c6b-72c9-4d01-a088-7e7821004e06"
            }
          ]
        },
        {
          "id": "c939c20a-75e4-4803-ad5f-28c0527edb54",
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
              "id": "044f641b-9138-4d54-883f-09b974c5ae4b"
            }
          ]
        },
        {
          "id": "86044f7a-482f-424d-ae14-3eef57723cef",
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
              "id": "10594688-740f-4fa6-a3bd-27ec9bf22401"
            }
          ]
        }
      ]
    },
    {
      "name": "Project",
      "item": [
        {
          "id": "058635cc-5be1-421e-ae5e-b2432172002f",
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
              "id": "b02040b7-afad-48ec-b04b-99c07602f70e"
            }
          ]
        }
      ]
    },
    {
      "name": "Remote Access Sessions",
      "item": [
        {
          "id": "88e5882c-045e-41a1-9bb7-f273cec4ea2f",
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
              "id": "98c43be7-6e6a-459d-b6b6-f0b9791167f3"
            }
          ]
        },
        {
          "id": "912f468a-c322-40e1-b151-bb1d0544e307",
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
              "id": "c6b6a1fb-3d76-4b96-bfa4-80d596009821"
            }
          ]
        },
        {
          "id": "f689a870-f419-426b-83b2-122f165213d9",
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
              "id": "9aa7d981-b15f-4fa5-b05e-5013fb70f87c"
            }
          ]
        },
        {
          "id": "8c062cb7-d204-4d54-9b4f-9694297ca118",
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
              "id": "8cee3309-0441-4ff6-bc2e-c64dc7a8c1d3"
            }
          ]
        },
        {
          "id": "ac969d56-3d33-474a-938a-7d873192fd94",
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
              "id": "ec5c3cc2-5473-4aa9-a1ef-fa39223edf2b"
            }
          ]
        }
      ]
    },
    {
      "name": "Upload",
      "item": [
        {
          "id": "ce21f1be-c9f5-4053-b90f-d9ddf7cb2ece",
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
              "id": "8c032cb9-7309-4fa1-8fab-b328d28b60a8"
            }
          ]
        },
        {
          "id": "f09915d4-a576-4417-baa8-79aece341e8d",
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
              "id": "708c74f1-6e84-496e-80d1-ed77e09c0506"
            }
          ]
        }
      ]
    },
    {
      "name": "Projects",
      "item": [
        {
          "id": "6651c48d-5146-4967-9c0b-d68a1fbba599",
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
              "id": "410a3622-1449-4e9e-81a5-6af4dcc9bba8"
            }
          ]
        },
        {
          "id": "b4c9eabe-8077-4306-8fdd-ef28a33c29a5",
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
              "id": "1bc90ee4-4376-485d-970f-12ad3c39ca41"
            }
          ]
        },
        {
          "id": "f2542a3d-509a-42c7-ac1e-de6f720cb160",
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
              "id": "ffad6562-c5e9-4383-b2cd-afe494a6f995"
            }
          ]
        }
      ]
    },
    {
      "name": "Runs",
      "item": [
        {
          "id": "eaf39cdd-92e1-4939-a784-0b704b7e2236",
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
              "id": "99b8063e-e213-450c-8b38-cc85d1ce9781"
            }
          ]
        },
        {
          "id": "28f303a6-266e-48dc-9c83-ff0944db93c0",
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
              "id": "1ef622ac-78f8-4545-8c11-b31be1ccf58b"
            }
          ]
        },
        {
          "id": "8e0d6744-8590-445e-a055-19d23ba36a89",
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
              "id": "91f969bb-562c-4a21-b529-c8441ba0ba80"
            }
          ]
        }
      ]
    },
    {
      "name": "Uploads",
      "item": [
        {
          "id": "9780fefc-cb84-47ac-88d2-5617dec19a06",
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
              "id": "a4e7f8b3-cabf-461b-ac9f-d1735091cefe"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Settings",
      "item": [
        {
          "id": "10d851d3-8baa-42e5-b545-d250f5ad22ae",
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
              "id": "9180ab26-df6a-4709-aad7-a9fc06e868d4"
            }
          ]
        }
      ]
    },
    {
      "name": "Devices",
      "item": [
        {
          "id": "3fd8d582-dd41-45ee-b6f4-bfb1082b51e4",
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
              "id": "34305b28-5bb0-4314-a8c7-f4108c806004"
            }
          ]
        },
        {
          "id": "e9b6b433-c90f-4f2b-b0e1-1563f736d45d",
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
              "id": "cc7a118e-83bd-4ae1-a888-14d5c4eefd97"
            }
          ]
        }
      ]
    },
    {
      "name": "Jobs",
      "item": [
        {
          "id": "00f7c67a-dd76-4e06-b963-89db09c48400",
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
              "id": "4928c7f4-02e9-4ba2-bc63-93f82baa6610"
            }
          ]
        },
        {
          "id": "d7628913-038f-4972-b5d0-c51f4d85c59d",
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
              "id": "8b72f9c1-3551-416a-ba15-ee96335d24a0"
            }
          ]
        }
      ]
    },
    {
      "name": "Offering Status",
      "item": [
        {
          "id": "f907ac99-1ec4-47f6-bf87-b59cb9f2ad50",
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
              "id": "88653c2e-a51f-482f-930c-b52a63d8fc0d"
            }
          ]
        }
      ]
    },
    {
      "name": "Suites",
      "item": [
        {
          "id": "0b6fb4f0-e1fd-4684-af49-c71d55b2de1c",
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
              "id": "7adb3b1d-b03a-46c6-bfaa-6d0e50fedccc"
            }
          ]
        },
        {
          "id": "67f66fb2-21d5-4608-908d-92d2df257af2",
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
              "id": "489b3599-4592-48c4-a2e1-2dbe6c0eaf6e"
            }
          ]
        }
      ]
    },
    {
      "name": "Tests",
      "item": [
        {
          "id": "52c9552e-a92e-4605-a1ec-a524ae5d4b09",
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
              "id": "87299591-a363-4ba3-941d-bfb52804c022"
            }
          ]
        },
        {
          "id": "a2b7a859-f935-4152-abde-747dc36c55ac",
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
              "id": "f58d14d0-cc56-412e-98b1-b8023ce22f4f"
            }
          ]
        }
      ]
    },
    {
      "name": "Artifacts",
      "item": [
        {
          "id": "5faea547-e7bc-4a91-8595-2c82bc173816",
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
              "id": "b65c1580-ef51-4da5-b246-21e727f7632d"
            }
          ]
        }
      ]
    },
    {
      "name": "Offerings",
      "item": [
        {
          "id": "4ed12c19-d9a1-4856-9d21-9609ac80d40c",
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
              "id": "5ed262dc-46ba-4825-ac60-ef83b182f003"
            }
          ]
        }
      ]
    },
    {
      "name": "Offering Transactions",
      "item": [
        {
          "id": "98934830-bd7c-4e74-ad5d-4c79cbc80ca7",
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
              "id": "0fb056db-40ac-4af9-961d-186d226f371f"
            }
          ]
        }
      ]
    },
    {
      "name": "Samples",
      "item": [
        {
          "id": "cde5da73-392d-427c-ad63-76c9f89718af",
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
              "id": "1425e822-d494-4a7b-9422-dca677d9d67a"
            }
          ]
        }
      ]
    },
    {
      "name": "Unique Problems",
      "item": [
        {
          "id": "e06fc55d-fcf5-4c14-a737-54f9d91504ae",
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
              "id": "01aebc0e-bf11-41fe-86dd-e74442d4e32c"
            }
          ]
        }
      ]
    }
  ]
}