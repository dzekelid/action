---
swagger: "2.0"
x-collection-name: AWS EC2 Systems Manager
x-complete: 0
info:
  title: Amazon EC2 Systems Manager API Create Document
  version: 1.0.0
  description: Creates an SSM document.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddTagsToResource:
    get:
      summary: Add Tags To Resource
      description: Adds or overwrites one or more tags for the specified resource.
      operationId: addTagsToResource
      x-api-path-slug: actionaddtagstoresource-get
      parameters:
      - in: query
        name: ResourceId
        description: The resource ID you want to tag
        type: string
      - in: query
        name: ResourceType
        description: Specifies the type of resource you are tagging
        type: string
      - in: query
        name: Tags
        description: One or more tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - Resources
  /?Action=CancelCommand:
    get:
      summary: Cancel Command
      description: Attempts to cancel the command specified by the Command ID.
      operationId: cancelCommand
      x-api-path-slug: actioncancelcommand-get
      parameters:
      - in: query
        name: CommandId
        description: The ID of the command you want to cancel
        type: string
      - in: query
        name: InstanceIds
        description: (Optional) A list of instance IDs on which you want to cancel
          the command
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cancel
      - Command
  /?Action=CreateActivation:
    get:
      summary: Create Activation
      description: |-
        Registers your on-premises server or virtual machine with Amazon EC2 so that you can manage
           these resources using Run Command.
      operationId: createActivation
      x-api-path-slug: actioncreateactivation-get
      parameters:
      - in: query
        name: DefaultInstanceName
        description: The name of the registered, managed instance as it will appear
          in the Amazon EC2 console or   when you use the AWS command line tools to
          list EC2 resources
        type: string
      - in: query
        name: Description
        description: A user-defined description of the resource that you want to register
          with Amazon EC2
        type: string
      - in: query
        name: ExpirationDate
        description: The date by which this activation request should expire
        type: string
      - in: query
        name: IamRole
        description: The Amazon Identity and Access Management (IAM) role that you
          want to assign to the   managed instance
        type: string
      - in: query
        name: RegistrationLimit
        description: Specify the maximum number of managed instances you want to register
        type: string
      responses:
        200:
          description: OK
      tags:
      - Activation
  /?Action=CreateAssociation:
    get:
      summary: Create Association
      description: Associates the specified SSM document with the specified instances
        or targets.
      operationId: createAssociation
      x-api-path-slug: actioncreateassociation-get
      parameters:
      - in: query
        name: DocumentVersion
        description: The document version you want to associate with the target(s)
        type: string
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      - in: query
        name: Name
        description: The name of the SSM document
        type: string
      - in: query
        name: OutputLocation
        description: An Amazon S3 bucket where you want to store the output details
          of the request
        type: string
      - in: query
        name: Parameters
        description: The parameters for the documents runtime configuration
        type: string
      - in: query
        name: ScheduleExpression
        description: A cron expression when the association will be applied to the
          target(s)
        type: string
      - in: query
        name: Targets
        description: The targets (either instances or tags) for the association
        type: string
      responses:
        200:
          description: OK
      tags:
      - Association
  /?Action=CreateAssociationBatch:
    get:
      summary: Create Association Batch
      description: Associates the specified SSM document with the specified instances
        or targets.
      operationId: createAssociationBatch
      x-api-path-slug: actioncreateassociationbatch-get
      parameters:
      - in: query
        name: Entries
        description: One or more associations
        type: string
      responses:
        200:
          description: OK
      tags:
      - Association
      - Batch
  /?Action=CreateDocument:
    get:
      summary: Create Document
      description: Creates an SSM document.
      operationId: createDocument
      x-api-path-slug: actioncreatedocument-get
      parameters:
      - in: query
        name: Content
        description: A valid JSON string
        type: string
      - in: query
        name: DocumentType
        description: The type of document to create
        type: string
      - in: query
        name: Name
        description: A name for the SSM document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Document
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