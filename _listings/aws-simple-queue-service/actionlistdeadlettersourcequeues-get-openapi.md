---
swagger: "2.0"
x-collection-name: AWS Simple Queue Service
x-complete: 0
info:
  title: AWS Simple Queue Service API List Dead Letter Source Queues
  version: 1.0.0
  description: Returns a list of your queues that have the RedrivePolicy queue attribute
    configured with a dead letter queue.
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
      description: Adds a permission to a queue for a specific.
      operationId: addPermission
      x-api-path-slug: actionaddpermission-get
      parameters:
      - in: query
        name: ActionName.N
        description: The action the client wants to allow for the specified principal
        type: string
      - in: query
        name: AWSAccountId.N
        description: The AWS account number of the principal who is given permission
        type: string
      - in: query
        name: Label
        description: The unique identification of the permission youre setting (for
          example, AliceSendMessage)
        type: string
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue to which permissions are added
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permissions
  /?Action=ChangeMessageVisibility:
    get:
      summary: Change Message Visibility
      description: Changes the visibility timeout of a specified message in a queue
        to a new value.
      operationId: changeMessageVisibility
      x-api-path-slug: actionchangemessagevisibility-get
      parameters:
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue whose messages visibility is
          changed
        type: string
      - in: query
        name: ReceiptHandle
        description: The receipt handle associated with the message whose visibility
          timeout is changed
        type: string
      - in: query
        name: VisibilityTimeout
        description: The new value for the messages visibility timeout (in seconds)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message Visibility
  /?Action=ChangeMessageVisibilityBatch:
    get:
      summary: Change Message Visibility Batch
      description: Changes the visibility timeout of multiple messages.
      operationId: changeMessageVisibilityBatch
      x-api-path-slug: actionchangemessagevisibilitybatch-get
      parameters:
      - in: query
        name: ChangeMessageVisibilityBatchRequestEntry.N
        description: A list of receipt handles of the messages for which the visibility
          timeout must be changed
        type: string
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue whose messages visibility is
          changed
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message Visibility
  /?Action=CreateQueue:
    get:
      summary: Create Queue
      description: Creates a new standard or FIFO queue or returns the URL of an existing
        queue.
      operationId: createQueue
      x-api-path-slug: actioncreatequeue-get
      parameters:
      - in: query
        name: |-
          Attribute
                      , Attribute.N.Name (key), Attribute.N.Value (value)
        description: A map of attributes with their corresponding values
        type: string
      - in: query
        name: QueueName
        description: The name of the new queue
        type: string
      responses:
        200:
          description: OK
      tags:
      - Queues
  /?Action=DeleteMessage:
    get:
      summary: Delete Message
      description: Deletes the specified message from the specified queue.
      operationId: deleteMessage
      x-api-path-slug: actiondeletemessage-get
      parameters:
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue from which messages are deleted
        type: string
      - in: query
        name: ReceiptHandle
        description: The receipt handle associated with the message to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Messages
  /?Action=DeleteMessageBatch:
    get:
      summary: Delete Message Batch
      description: Deletes up to ten messages from the specified queue.
      operationId: deleteMessageBatch
      x-api-path-slug: actiondeletemessagebatch-get
      parameters:
      - in: query
        name: DeleteMessageBatchRequestEntry.N
        description: A list of receipt handles for the messages to be deleted
        type: string
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue from which messages are deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Messages
  /?Action=DeleteQueue:
    get:
      summary: Delete Queue
      description: Deletes the queue specified by the QueueUrl, even if the queue
        is empty.
      operationId: deleteQueue
      x-api-path-slug: actiondeletequeue-get
      parameters:
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Queues
  /?Action=GetQueueAttributes:
    get:
      summary: Get Queue Attributes
      description: Gets attributes for the specified queue.
      operationId: getQueueAttributes
      x-api-path-slug: actiongetqueueattributes-get
      parameters:
      - in: query
        name: AttributeName.N
        description: A list of attributes for which to retrieve information
        type: string
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue whose attribute information is
          retrieved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Queues
  /?Action=GetQueueUrl:
    get:
      summary: Get Queue Url
      description: Returns the URL of an existing queue.
      operationId: getQueueUrl
      x-api-path-slug: actiongetqueueurl-get
      parameters:
      - in: query
        name: QueueName
        description: The name of the queue whose URL must be fetched
        type: string
      - in: query
        name: QueueOwnerAWSAccountId
        description: The AWS account ID of the account that created the queue
        type: string
      responses:
        200:
          description: OK
      tags:
      - Queues
  /?Action=ListDeadLetterSourceQueues:
    get:
      summary: List Dead Letter Source Queues
      description: Returns a list of your queues that have the RedrivePolicy queue
        attribute configured with a dead letter queue.
      operationId: listDeadLetterSourceQueues
      x-api-path-slug: actionlistdeadlettersourcequeues-get
      parameters:
      - in: query
        name: QueueUrl
        description: The URL of a dead letter queue
        type: string
      responses:
        200:
          description: OK
      tags:
      - Queues
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