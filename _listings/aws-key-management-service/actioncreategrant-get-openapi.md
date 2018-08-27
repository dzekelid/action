---
swagger: "2.0"
x-collection-name: AWS Key Management Service
x-complete: 0
info:
  title: AWS Key Management Service API Create Grant
  version: 1.0.0
  description: Adds a grant to a key to specify who can use the key and under what
    conditions.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CancelKeyDeletion:
    get:
      summary: Cancel Key Deletion
      description: Cancels the deletion of a customer master key (CMK).
      operationId: cancelKeyDeletion
      x-api-path-slug: actioncancelkeydeletion-get
      parameters:
      - in: query
        name: KeyId
        description: The unique identifier for the customer master key (CMK) for which
          to cancel      deletion
        type: string
      responses:
        200:
          description: OK
      tags:
      - Keys
  /?Action=CreateAlias:
    get:
      summary: Create Alias
      description: Creates a display name for a customer master key.
      operationId: createAlias
      x-api-path-slug: actioncreatealias-get
      parameters:
      - in: query
        name: AliasName
        description: String that contains the display name
        type: string
      - in: query
        name: TargetKeyId
        description: An identifier of the key for which you are creating the alias
        type: string
      responses:
        200:
          description: OK
      tags:
      - Aliases
  /?Action=CreateGrant:
    get:
      summary: Create Grant
      description: Adds a grant to a key to specify who can use the key and under
        what conditions.
      operationId: createGrant
      x-api-path-slug: actioncreategrant-get
      parameters:
      - in: query
        name: Constraints
        description: The conditions under which the operations permitted by the grant
          are allowed
        type: string
      - in: query
        name: GranteePrincipal
        description: The principal that is given permission to perform the operations
          that the grant      permits
        type: string
      - in: query
        name: GrantTokens
        description: A list of grant tokens
        type: string
      - in: query
        name: KeyId
        description: The unique identifier for the customer master key (CMK) that
          the grant applies      to
        type: string
      - in: query
        name: Name
        description: A friendly name for identifying the grant
        type: string
      - in: query
        name: Operations
        description: A list of operations that the grant permits
        type: string
      - in: query
        name: RetiringPrincipal
        description: The principal that is given permission to retire the grant by
          using RetireGrant operation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Grants
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