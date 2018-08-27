---
swagger: "2.0"
x-collection-name: AWS Simple Notification Service
x-complete: 0
info:
  title: AWS Simple Notification Service API Create Platform Application
  version: 1.0.0
  description: |-
    Creates a platform application object for one of the supported push notification services,
          such as APNS and GCM, to which devices and mobile apps may register.
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
      description: Adds a statement to a topic's access control policy, granting access
        for the specified AWS accounts to the specified actions.
      operationId: addPermission
      x-api-path-slug: actionaddpermission-get
      parameters:
      - in: query
        name: ActionName.member.N
        description: The action you want to allow for the specified principal(s)
        type: string
      - in: query
        name: AWSAccountId.member.N
        description: The AWS account IDs of the users (principals) who will be given
          access to the specified actions
        type: string
      - in: query
        name: Label
        description: A unique identifier for the new policy statement
        type: string
      - in: query
        name: TopicArn
        description: The ARN of the topic whose access control policy you wish to
          modify
        type: string
      responses:
        200:
          description: OK
      tags:
      - Permissions
  /?Action=CheckIfPhoneNumberIsOptedOut:
    get:
      summary: Check If Phone Number Is Opted Out
      description: Accepts a phone number and indicates whether the phone holder has
        opted out of receiving SMS messages from your account.
      operationId: checkIfPhoneNumberIsOptedOut
      x-api-path-slug: actioncheckifphonenumberisoptedout-get
      parameters:
      - in: query
        name: phoneNumber
        description: The phone number for which you want to check the opt out status
        type: string
      responses:
        200:
          description: OK
      tags:
      - Opt Out
  /?Action=ConfirmSubscription:
    get:
      summary: Confirm Subscription
      description: |-
        Verifies an endpoint owner's intent to receive messages by validating the token sent to the
              endpoint by an earlier Subscribe action.
      operationId: confirmSubscription
      x-api-path-slug: actionconfirmsubscription-get
      parameters:
      - in: query
        name: AuthenticateOnUnsubscribe
        description: Disallows unauthenticated unsubscribes of the subscription
        type: string
      - in: query
        name: Token
        description: Short-lived token sent to an endpoint during the Subscribe action
        type: string
      - in: query
        name: TopicArn
        description: The ARN of the topic for which you wish to confirm a subscription
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subscriptions
  /?Action=CreatePlatformApplication:
    get:
      summary: Create Platform Application
      description: |-
        Creates a platform application object for one of the supported push notification services,
              such as APNS and GCM, to which devices and mobile apps may register.
      operationId: createPlatformApplication
      x-api-path-slug: actioncreateplatformapplication-get
      parameters:
      - in: query
        name: |-
          Attributes
                      , Attributes.entry.N.key (key), Attributesentry.N.value (value)
        description: For a list of attributes, see SetPlatformApplicationAttributes
        type: string
      - in: query
        name: Name
        description: Application names must be made up of only uppercase and lowercase
          ASCII letters, numbers, underscores, hyphens, and periods, and must be between
          1 and 256 characters long
        type: string
      - in: query
        name: Platform
        description: 'The following platforms are supported: ADM (Amazon Device Messaging),
          APNS (Apple Push Notification Service), APNS_SANDBOX, and GCM (Google Cloud
          Messaging)'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Platform Applications
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