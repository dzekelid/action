---
swagger: "2.0"
x-collection-name: AWS Lambda
x-complete: 0
info:
  title: AWS Lambda API Create Event Source Mapping
  version: 1.0.0
  description: Identifies a stream as an event source for a Lambda function.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddPermission:
    get:
      summary: Add Permission
      description: Adds a permission to the resource policy associated with the specified
        AWS Lambda function.
      operationId: addPermission
      x-api-path-slug: actionaddpermission-get
      parameters:
      - in: query
        name: FunctionName
        description: Name of the Lambda function whose resource policy you are updating
          by adding a new permission
        type: string
      - in: query
        name: Qualifier
        description: You can use this optional query parameter to describe a qualified
          ARN using a function version or an alias name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permissions
  /?Action=CreateAlias:
    get:
      summary: Create Alias
      description: Creates an alias that points to the specified Lambda function version.
      operationId: createAlias
      x-api-path-slug: actioncreatealias-get
      parameters:
      - in: query
        name: FunctionName
        description: Name of the Lambda function for which you want to create an alias
        type: string
      responses:
        200:
          description: OK
      tags:
      - Aliases
  /?Action=CreateEventSourceMapping:
    get:
      summary: Create Event Source Mapping
      description: Identifies a stream as an event source for a Lambda function.
      operationId: createEventSourceMapping
      x-api-path-slug: actioncreateeventsourcemapping-get
      parameters:
      - in: query
        name: BatchSize
        description: The largest number of records that AWS Lambda will retrieve from
          your event source at the time of invoking your function
        type: string
      - in: query
        name: Enabled
        description: Indicates whether AWS Lambda should begin polling the event source
        type: string
      - in: query
        name: EventSourceArn
        description: The Amazon Resource Name (ARN) of the Amazon Kinesis or the Amazon
          DynamoDB stream that is the event source
        type: string
      - in: query
        name: FunctionName
        description: The Lambda function to invoke when AWS Lambda detects an event
          on the stream
        type: string
      - in: query
        name: StartingPosition
        description: The position in the stream where AWS Lambda should start reading
        type: string
      - in: query
        name: StartingPositionTimestamp
        description: The timestamp of the data record from which to start reading
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event Sources
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