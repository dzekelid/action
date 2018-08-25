---
swagger: "2.0"
x-collection-name: AWS WorkDocs
x-complete: 0
info:
  title: AWS WorkDocs API Create Notification Subscription
  version: 1.0.0
  description: Configure WorkDocs to use Amazon SNS notifications.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AbortDocumentVersionUpload:
    get:
      summary: Abort Document Version Upload
      description: Aborts the upload of the specified document version that was previously
        initiated by.
      operationId: abortDocumentVersionUpload
      x-api-path-slug: actionabortdocumentversionupload-get
      parameters:
      - in: query
        name: DocumentId
        description: The ID of the document
        type: string
      - in: query
        name: VersionId
        description: The ID of the version
        type: string
      responses:
        200:
          description: OK
      tags:
      - Documents
  /?Action=ActivateUser:
    get:
      summary: Activate User
      description: Activates the specified user.
      operationId: activateUser
      x-api-path-slug: actionactivateuser-get
      parameters:
      - in: query
        name: UserId
        description: The ID of the user
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
  /?Action=AddResourcePermissions:
    get:
      summary: Add Resource Permissions
      description: Creates a set of permissions for the specified folder or document.
      operationId: addResourcePermissions
      x-api-path-slug: actionaddresourcepermissions-get
      parameters:
      - in: query
        name: ResourceId
        description: The ID of the resource
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permissions
  /?Action=CreateFolder:
    get:
      summary: Create Folder
      description: Creates a folder with the specified name and parent folder.
      operationId: createFolder
      x-api-path-slug: actioncreatefolder-get
      parameters:
      - in: query
        name: Name
        description: The name of the new folder
        type: string
      - in: query
        name: ParentFolderId
        description: The ID of the parent folder
        type: string
      responses:
        200:
          description: OK
      tags:
      - Folders
  /?Action=CreateNotificationSubscription:
    get:
      summary: Create Notification Subscription
      description: Configure WorkDocs to use Amazon SNS notifications.
      operationId: createNotificationSubscription
      x-api-path-slug: actioncreatenotificationsubscription-get
      parameters:
      - in: query
        name: OrganizationId
        description: The ID of the organization
        type: string
      responses:
        200:
          description: OK
      tags:
      - Notifications
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