---
swagger: "2.0"
x-collection-name: AWS WAF
x-complete: 0
info:
  title: AWS WAF API Create Byte Match Set
  version: 1.0.0
  description: 'Service: AWS WAFCreates a ByteMatchSet.'
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AssociateWebACL:
    get:
      summary: Associate Web ACL
      description: 'Service: AWS WAF RegionalAssociates a web ACL with a resource.'
      operationId: associateWebACL
      x-api-path-slug: actionassociatewebacl-get
      parameters:
      - in: query
        name: ResourceArn
        description: The ARN (Amazon Resource Name) of the resource to be protected
        type: string
      - in: query
        name: WebACLId
        description: A unique identifier (ID) for the web ACL
        type: string
      responses:
        200:
          description: OK
      tags:
      - Web ACL
  /?Action=CreateByteMatchSet:
    get:
      summary: Create Byte Match Set
      description: 'Service: AWS WAFCreates a ByteMatchSet.'
      operationId: createByteMatchSet
      x-api-path-slug: actioncreatebytematchset-get
      parameters:
      - in: query
        name: ChangeToken
        description: The value returned by the most recent call to GetChangeToken
        type: string
      - in: query
        name: Name
        description: A friendly name or description of the ByteMatchSet
        type: string
      responses:
        200:
          description: OK
      tags:
      - Byte Match Set
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