---
name: AWS Simple Notification Service
x-slug: aws-simple-notification-service
description: Amazon Simple Notification Service (Amazon SNS) is a fast, flexible,
  fully managed push notification service that lets you send individual messages or
  to fan-out messages to large numbers of recipients. Amazon SNS makes it simple and
  cost effective to send push notifications to mobile device users, email recipients
  or even send messages to other distributed services.With Amazon SNS, you can send
  notifications to Apple, Google, Fire OS, and Windows devices, as well as to Android
  devices in China with Baidu Cloud Push. You can use SNS to send SMS messages to
  mobile device users worldwide.Beyond these endpoints, Amazon SNS can also deliver
  messages toAmazon Simple Queue Service(SQS),AWS Lambda functions, or to any HTTP
  endpoint.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Action
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Simple Notification Service API - Add Permission
  x-api-slug: actionaddpermission-get
  description: Adds a statement to a topic's access control policy, granting access
    for the specified AWS accounts to the specified actions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionaddpermission-get-openapi.md
- name: AWS Simple Notification Service API - Check If Phone Number Is Opted Out
  x-api-slug: actioncheckifphonenumberisoptedout-get
  description: Accepts a phone number and indicates whether the phone holder has opted
    out of receiving SMS messages from your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actioncheckifphonenumberisoptedout-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actioncheckifphonenumberisoptedout-get-openapi.md
- name: AWS Simple Notification Service API - Confirm Subscription
  x-api-slug: actionconfirmsubscription-get
  description: |-
    Verifies an endpoint owner's intent to receive messages by validating the token sent to the
          endpoint by an earlier Subscribe action.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionconfirmsubscription-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionconfirmsubscription-get-openapi.md
- name: AWS Simple Notification Service API - Create Platform Application
  x-api-slug: actioncreateplatformapplication-get
  description: |-
    Creates a platform application object for one of the supported push notification services,
          such as APNS and GCM, to which devices and mobile apps may register.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actioncreateplatformapplication-get-openapi.md
- name: AWS Simple Notification Service API - Create Platform Endpoint
  x-api-slug: actioncreateplatformendpoint-get
  description: |-
    Creates an endpoint for a device and mobile app on one of the supported push notification
          services, such as GCM and APNS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actioncreateplatformendpoint-get-openapi.md
- name: AWS Simple Notification Service API - Create Topic
  x-api-slug: actioncreatetopic-get
  description: Creates a topic to which notifications can be published.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actioncreatetopic-get-openapi.md
- name: AWS Simple Notification Service API - Delete Endpoint
  x-api-slug: actiondeleteendpoint-get
  description: Deletes the endpoint for a device and mobile app from Amazon SNS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actiondeleteendpoint-get-openapi.md
- name: AWS Simple Notification Service API - Delete Platform Application
  x-api-slug: actiondeleteplatformapplication-get
  description: |-
    Deletes a platform application object for one of the supported push notification services,
          such as APNS and GCM.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actiondeleteplatformapplication-get-openapi.md
- name: AWS Simple Notification Service API - Delete Topic
  x-api-slug: actiondeletetopic-get
  description: Deletes a topic and all its subscriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actiondeletetopic-get-openapi.md
- name: AWS Simple Notification Service API - Get Endpoint Attributes
  x-api-slug: actiongetendpointattributes-get
  description: |-
    Retrieves the endpoint attributes for a device on one of the supported push notification
          services, such as GCM and APNS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actiongetendpointattributes-get-openapi.md
- name: AWS Simple Notification Service API - Get Platform Application Attributes
  x-api-slug: actiongetplatformapplicationattributes-get
  description: |-
    Retrieves the attributes of the platform application object for the supported push
          notification services, such as APNS and GCM.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actiongetplatformapplicationattributes-get-openapi.md
- name: AWS Simple Notification Service API - Get S M S Attributes
  x-api-slug: actiongetsmsattributes-get
  description: Returns the settings for sending SMS messages from your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actiongetsmsattributes-get-openapi.md
- name: AWS Simple Notification Service API - Get Subscription Attributes
  x-api-slug: actiongetsubscriptionattributes-get
  description: Returns all of the properties of a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actiongetsubscriptionattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actiongetsubscriptionattributes-get-openapi.md
- name: AWS Simple Notification Service API - Get Topic Attributes
  x-api-slug: actiongettopicattributes-get
  description: Returns all of the properties of a topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actiongettopicattributes-get-openapi.md
- name: AWS Simple Notification Service API - List Endpoints By Platform Application
  x-api-slug: actionlistendpointsbyplatformapplication-get
  description: |-
    Lists the endpoints and endpoint attributes for devices in a supported push notification
          service, such as GCM and APNS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionlistendpointsbyplatformapplication-get-openapi.md
- name: AWS Simple Notification Service API - List Phone Numbers Opted Out
  x-api-slug: actionlistphonenumbersoptedout-get
  description: Returns a list of phone numbers that are opted out, meaning you cannot
    send SMS messages to them.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionlistphonenumbersoptedout-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionlistphonenumbersoptedout-get-openapi.md
- name: AWS Simple Notification Service API - List Platform Applications
  x-api-slug: actionlistplatformapplications-get
  description: |-
    Lists the platform application objects for the supported push notification services, such as
          APNS and GCM.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionlistplatformapplications-get-openapi.md
- name: AWS Simple Notification Service API - List Subscriptions
  x-api-slug: actionlistsubscriptions-get
  description: Returns a list of the requester's subscriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionlistsubscriptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionlistsubscriptions-get-openapi.md
- name: AWS Simple Notification Service API - List Subscriptions By Topic
  x-api-slug: actionlistsubscriptionsbytopic-get
  description: Returns a list of the subscriptions to a specific topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionlistsubscriptionsbytopic-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionlistsubscriptionsbytopic-get-openapi.md
- name: AWS Simple Notification Service API - List Topics
  x-api-slug: actionlisttopics-get
  description: Returns a list of the requester's topics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionlisttopics-get-openapi.md
- name: AWS Simple Notification Service API - Opt In Phone Number
  x-api-slug: actionoptinphonenumber-get
  description: Use this request to opt in a phone number that is opted out, which
    enables you to resume sending SMS messages to the number.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionoptinphonenumber-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionoptinphonenumber-get-openapi.md
- name: AWS Simple Notification Service API - Publish
  x-api-slug: actionpublish-get
  description: Sends a message to all of a topic's subscribed endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionpublish-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionpublish-get-openapi.md
- name: AWS Simple Notification Service API - Remove Permission
  x-api-slug: actionremovepermission-get
  description: Removes a statement from a topic's access control policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionremovepermission-get-openapi.md
- name: AWS Simple Notification Service API - Set Endpoint Attributes
  x-api-slug: actionsetendpointattributes-get
  description: |-
    Sets the attributes for an endpoint for a device on one of the supported push notification
          services, such as GCM and APNS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionsetendpointattributes-get-openapi.md
- name: AWS Simple Notification Service API - Set Platform Application Attributes
  x-api-slug: actionsetplatformapplicationattributes-get
  description: |-
    Sets the attributes of the platform application object for the supported push notification
          services, such as APNS and GCM.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionsetplatformapplicationattributes-get-openapi.md
- name: AWS Simple Notification Service API - Set SMS Attributes
  x-api-slug: actionsetsmsattributes-get
  description: Use this request to set the default settings for sending SMS messages
    and receiving daily SMS usage reports.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionsetsmsattributes-get-openapi.md
- name: AWS Simple Notification Service API - Set Subscription Attributes
  x-api-slug: actionsetsubscriptionattributes-get
  description: Allows a subscription owner to set an attribute of the topic to a new
    value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionsetsubscriptionattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionsetsubscriptionattributes-get-openapi.md
- name: AWS Simple Notification Service API - Set Topic Attributes
  x-api-slug: actionsettopicattributes-get
  description: Allows a topic owner to set an attribute of the topic to a new value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionsettopicattributes-get-openapi.md
- name: AWS Simple Notification Service API - Subscribe
  x-api-slug: actionsubscribe-get
  description: Prepares to subscribe an endpoint by sending the endpoint a confirmation
    message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionsubscribe-get-openapi.md
- name: AWS Simple Notification Service API - Unsubscribe
  x-api-slug: actionunsubscribe-get
  description: Deletes a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Mobile-Services_AmazonSNS.png
  humanURL: https://aws.amazon.com/sns/
  baseURL: :///
  tags: Amazon Web Services, Notifications, SMS, Stack Network, API Service Provider,
    API Service Provider, API Provider, Messages, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionunsubscribe-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-simple-notification-service/actionunsubscribe-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.simple.email.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.simple.notification.service.stack.network
- type: x-change-log
  url: http://aws.amazon.com/releasenotes/Amazon-SN
- type: x-console
  url: https://console.aws.amazon.com/sns
- type: x-documentation
  url: http://docs.aws.amazon.com/sns/latest/api/
- type: x-faq
  url: https://aws.amazon.com/sns/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=72
- type: x-getting-started
  url: https://aws.amazon.com/sns/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/sns/pricing/
- type: x-website
  url: https://aws.amazon.com/sns/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---