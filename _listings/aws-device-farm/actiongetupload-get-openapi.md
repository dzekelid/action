---
swagger: "2.0"
x-collection-name: AWS Device Farm
x-complete: 0
info:
  title: AWS Device Farm API Get Upload
  version: 1.0.0
  description: Gets information about an upload.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateDevicePool:
    get:
      summary: Create Device Pool
      description: Creates a device pool.
      operationId: createDevicePool
      x-api-path-slug: actioncreatedevicepool-get
      parameters:
      - in: query
        name: description
        description: The device pools description
        type: string
      - in: query
        name: name
        description: The device pools name
        type: string
      - in: query
        name: projectArn
        description: The ARN of the project for the device pool
        type: string
      - in: query
        name: rules
        description: The device pools rules
        type: string
      responses:
        200:
          description: OK
      tags:
      - Device Pool
  /?Action=CreateProject:
    get:
      summary: Create Project
      description: Creates a new project.
      operationId: createProject
      x-api-path-slug: actioncreateproject-get
      parameters:
      - in: query
        name: name
        description: The projects name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Project
  /?Action=CreateRemoteAccessSession:
    get:
      summary: Create Remote Access Session
      description: Specifies and starts a remote access session.
      operationId: createRemoteAccessSession
      x-api-path-slug: actioncreateremoteaccesssession-get
      parameters:
      - in: query
        name: configuration
        description: The configuration information for the remote access session request
        type: string
      - in: query
        name: deviceArn
        description: The Amazon Resource Name (ARN) of the device for which you want
          to create a remote access session
        type: string
      - in: query
        name: name
        description: The name of the remote access session that you wish to create
        type: string
      - in: query
        name: projectArn
        description: The Amazon Resource Name (ARN) of the project for which you want
          to create a remote access session
        type: string
      responses:
        200:
          description: OK
      tags:
      - Remote Access Sessions
  /?Action=CreateUpload:
    get:
      summary: Create Upload
      description: Uploads an app or test scripts.
      operationId: createUpload
      x-api-path-slug: actioncreateupload-get
      parameters:
      - in: query
        name: contentType
        description: The uploads content type (for example, application/octet-stream)
        type: string
      - in: query
        name: name
        description: The uploads file name
        type: string
      - in: query
        name: projectArn
        description: The ARN of the project for the upload
        type: string
      - in: query
        name: type
        description: The uploads upload type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Upload
  /?Action=DeleteDevicePool:
    get:
      summary: Delete Device Pool
      description: Deletes a device pool given the pool ARN.
      operationId: deleteDevicePool
      x-api-path-slug: actiondeletedevicepool-get
      parameters:
      - in: query
        name: arn
        description: Represents the Amazon Resource Name (ARN) of the Device Farm
          device pool you wish to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Device Pool
  /?Action=DeleteProject:
    get:
      summary: Delete Project
      description: Deletes an AWS Device Farm project, given the project ARN.
      operationId: deleteProject
      x-api-path-slug: actiondeleteproject-get
      parameters:
      - in: query
        name: arn
        description: Represents the Amazon Resource Name (ARN) of the Device Farm
          project you wish to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Projects
  /?Action=DeleteRemoteAccessSession:
    get:
      summary: Delete Remote Access Session
      description: Deletes a completed remote access session and its results.
      operationId: deleteRemoteAccessSession
      x-api-path-slug: actiondeleteremoteaccesssession-get
      parameters:
      - in: query
        name: arn
        description: The Amazon Resource Name (ARN) of the sesssion for which you
          want to delete remote access
        type: string
      responses:
        200:
          description: OK
      tags:
      - Remote Access Sessions
  /?Action=DeleteRun:
    get:
      summary: Delete Run
      description: Deletes the run, given the run ARN.
      operationId: deleteRun
      x-api-path-slug: actiondeleterun-get
      parameters:
      - in: query
        name: arn
        description: The Amazon Resource Name (ARN) for the run you wish to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Runs
  /?Action=DeleteUpload:
    get:
      summary: Delete Upload
      description: Deletes an upload given the upload ARN.
      operationId: deleteUpload
      x-api-path-slug: actiondeleteupload-get
      parameters:
      - in: query
        name: arn
        description: Represents the Amazon Resource Name (ARN) of the Device Farm
          upload you wish to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Uploads
  /?Action=GetAccountSettings:
    get:
      summary: Get Account Settings
      description: Returns the number of unmetered iOS and/or unmetered Android devices
        that have been purchased by the account.
      operationId: getAccountSettings
      x-api-path-slug: actiongetaccountsettings-get
      parameters:
      - in: query
        name: accountSettings
        description: A container for account-level settings within AWS Device Farm
        type: string
      responses:
        200:
          description: OK
      tags:
      - Account Settings
  /?Action=GetDevice:
    get:
      summary: Get Device
      description: Gets information about a unique device type.
      operationId: getDevice
      x-api-path-slug: actiongetdevice-get
      parameters:
      - in: query
        name: arn
        description: The device types ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - Devices
  /?Action=GetDevicePool:
    get:
      summary: Get Device Pool
      description: Gets information about a device pool.
      operationId: getDevicePool
      x-api-path-slug: actiongetdevicepool-get
      parameters:
      - in: query
        name: arn
        description: The device pools ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - Device Pool
  /?Action=GetDevicePoolCompatibility:
    get:
      summary: Get Device Pool Compatibility
      description: Gets information about compatibility with a device pool.
      operationId: getDevicePoolCompatibility
      x-api-path-slug: actiongetdevicepoolcompatibility-get
      parameters:
      - in: query
        name: appArn
        description: The ARN of the app that is associated with the specified device
          pool
        type: string
      - in: query
        name: devicePoolArn
        description: The device pools ARN
        type: string
      - in: query
        name: testType
        description: The test type for the specified device pool
        type: string
      responses:
        200:
          description: OK
      tags:
      - Device Pool
  /?Action=GetJob:
    get:
      summary: Get Job
      description: Gets information about a job.
      operationId: getJob
      x-api-path-slug: actiongetjob-get
      parameters:
      - in: query
        name: arn
        description: The jobs ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - Jobs
  /?Action=GetOfferingStatus:
    get:
      summary: Get Offering Status
      description: Gets the current status and future status of all offerings purchased
        by an AWS account.
      operationId: getOfferingStatus
      x-api-path-slug: actiongetofferingstatus-get
      parameters:
      - in: query
        name: nextToken
        description: An identifier that was returned from the previous call to this
          operation, which can be used to return the next set of items in the list
        type: string
      responses:
        200:
          description: OK
      tags:
      - Offering Status
  /?Action=GetProject:
    get:
      summary: Get Project
      description: Gets information about a project.
      operationId: getProject
      x-api-path-slug: actiongetproject-get
      parameters:
      - in: query
        name: arn
        description: The projects ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - Projects
  /?Action=GetRemoteAccessSession:
    get:
      summary: Get Remote Access Session
      description: Returns a link to a currently running remote access session.
      operationId: getRemoteAccessSession
      x-api-path-slug: actiongetremoteaccesssession-get
      parameters:
      - in: query
        name: arn
        description: The Amazon Resource Name (ARN) of the remote access session about
          which you want to get session information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Remote Access Sessions
  /?Action=GetRun:
    get:
      summary: Get Run
      description: Gets information about a run.
      operationId: getRun
      x-api-path-slug: actiongetrun-get
      parameters:
      - in: query
        name: arn
        description: The runs ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - Runs
  /?Action=GetSuite:
    get:
      summary: Get Suite
      description: Gets information about a suite.
      operationId: getSuite
      x-api-path-slug: actiongetsuite-get
      parameters:
      - in: query
        name: arn
        description: The suites ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - Suites
  /?Action=GetTest:
    get:
      summary: Get Test
      description: Gets information about a test.
      operationId: getTest
      x-api-path-slug: actiongettest-get
      parameters:
      - in: query
        name: arn
        description: The tests ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tests
  /?Action=GetUpload:
    get:
      summary: Get Upload
      description: Gets information about an upload.
      operationId: getUpload
      x-api-path-slug: actiongetupload-get
      parameters:
      - in: query
        name: arn
        description: The uploads ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - Upload
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---