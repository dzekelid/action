---
name: AWS Inspector
x-slug: aws-inspector
description: Amazon Inspector is an automated security assessment service that helps
  improve the security and compliance of applications deployed on AWS. Amazon Inspector
  automatically assesses applications for vulnerabilities or deviations from best
  practices. After performing an assessment, Amazon Inspector produces a detailed
  list of security findings prioritized by level of severity.To help you get started
  quickly, Amazon Inspector includes a knowledge base of hundreds of rules mapped
  to common security best practices and vulnerability definitions. Examples of built-in
  rules include checking for remote root login being enabled, or vulnerable software
  versions installed. These rules are regularly updated by AWS security researchers.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Action
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Inspector API - Add Attributes To Findings
  x-api-slug: actionaddattributestofindings-get
  description: |-
    Assigns attributes (key and value pairs) to the findings that are specified by the
             ARNs of the findings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionaddattributestofindings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionaddattributestofindings-get-openapi.md
- name: AWS Inspector API - Create Assessment Target
  x-api-slug: actioncreateassessmenttarget-get
  description: |-
    Creates a new assessment target using the ARN of the resource group that is generated
             by.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actioncreateassessmenttarget-get-openapi.md
- name: AWS Inspector API - Create Assessment Template
  x-api-slug: actioncreateassessmenttemplate-get
  description: |-
    Creates an assessment template for the assessment target that is specified by the ARN
             of the assessment target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actioncreateassessmenttemplate-get-openapi.md
- name: AWS Inspector API - Create Resource Group
  x-api-slug: actioncreateresourcegroup-get
  description: |-
    Creates a resource group using the specified set of tags (key and value pairs) that
             are used to select the EC2 instances to be included in an Amazon Inspector assessment
             target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actioncreateresourcegroup-get-openapi.md
- name: AWS Inspector API - Delete Assessment Run
  x-api-slug: actiondeleteassessmentrun-get
  description: |-
    Deletes the assessment run that is specified by the ARN of the assessment
             run.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actiondeleteassessmentrun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actiondeleteassessmentrun-get-openapi.md
- name: AWS Inspector API - Delete Assessment Target
  x-api-slug: actiondeleteassessmenttarget-get
  description: |-
    Deletes the assessment target that is specified by the ARN of the assessment
             target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actiondeleteassessmenttarget-get-openapi.md
- name: AWS Inspector API - Delete Assessment Template
  x-api-slug: actiondeleteassessmenttemplate-get
  description: |-
    Deletes the assessment template that is specified by the ARN of the assessment
             template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actiondeleteassessmenttemplate-get-openapi.md
- name: AWS Inspector API - Describe Assessment Runs
  x-api-slug: actiondescribeassessmentruns-get
  description: |-
    Describes the assessment runs that are specified by the ARNs of the assessment
             runs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actiondescribeassessmentruns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actiondescribeassessmentruns-get-openapi.md
- name: AWS Inspector API - Describe Assessment Targets
  x-api-slug: actiondescribeassessmenttargets-get
  description: |-
    Describes the assessment targets that are specified by the ARNs of the assessment
             targets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actiondescribeassessmenttargets-get-openapi.md
- name: AWS Inspector API - Describe Assessment Templates
  x-api-slug: actiondescribeassessmenttemplates-get
  description: |-
    Describes the assessment templates that are specified by the ARNs of the assessment
             templates.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actiondescribeassessmenttemplates-get-openapi.md
- name: AWS Inspector API - Describe Cross Account Access Role
  x-api-slug: actiondescribecrossaccountaccessrole-get
  description: |-
    Describes the IAM role that enables Amazon Inspector to access your AWS
             account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actiondescribecrossaccountaccessrole-get-openapi.md
- name: AWS Inspector API - Describe Findings
  x-api-slug: actiondescribefindings-get
  description: Describes the findings that are specified by the ARNs of the findings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actiondescribefindings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actiondescribefindings-get-openapi.md
- name: AWS Inspector API - Describe Resource Groups
  x-api-slug: actiondescriberesourcegroups-get
  description: |-
    Describes the resource groups that are specified by the ARNs of the resource
             groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actiondescriberesourcegroups-get-openapi.md
- name: AWS Inspector API - Describe Rules Packages
  x-api-slug: actiondescriberulespackages-get
  description: |-
    Describes the rules packages that are specified by the ARNs of the rules
             packages.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actiondescriberulespackages-get-openapi.md
- name: AWS Inspector API - Get Telemetry Metadata
  x-api-slug: actiongettelemetrymetadata-get
  description: |-
    Information about the data that is collected for the specified assessment
             run.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actiongettelemetrymetadata-get-openapi.md
- name: AWS Inspector API - List Assessment Run Agents
  x-api-slug: actionlistassessmentrunagents-get
  description: |-
    Lists the agents of the assessment runs that are specified by the ARNs of the
             assessment runs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionlistassessmentrunagents-get-openapi.md
- name: AWS Inspector API - List Assessment Runs
  x-api-slug: actionlistassessmentruns-get
  description: |-
    Lists the assessment runs that correspond to the assessment templates that are
             specified by the ARNs of the assessment templates.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionlistassessmentruns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionlistassessmentruns-get-openapi.md
- name: AWS Inspector API - List Assessment Targets
  x-api-slug: actionlistassessmenttargets-get
  description: Lists the ARNs of the assessment targets within this AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionlistassessmenttargets-get-openapi.md
- name: AWS Inspector API - List Assessment Templates
  x-api-slug: actionlistassessmenttemplates-get
  description: |-
    Lists the assessment templates that correspond to the assessment targets that are
             specified by the ARNs of the assessment targets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionlistassessmenttemplates-get-openapi.md
- name: AWS Inspector API - List Event Subscriptions
  x-api-slug: actionlisteventsubscriptions-get
  description: |-
    Lists all the event subscriptions for the assessment template that is specified by
             the ARN of the assessment template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionlisteventsubscriptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionlisteventsubscriptions-get-openapi.md
- name: AWS Inspector API - List Findings
  x-api-slug: actionlistfindings-get
  description: |-
    Lists findings that are generated by the assessment runs that are specified by the
             ARNs of the assessment runs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionlistfindings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionlistfindings-get-openapi.md
- name: AWS Inspector API - List Rules Packages
  x-api-slug: actionlistrulespackages-get
  description: Lists all available Amazon Inspector rules packages.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionlistrulespackages-get-openapi.md
- name: AWS Inspector API - List Tags For Resource
  x-api-slug: actionlisttagsforresource-get
  description: Lists all tags associated with an assessment template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionlisttagsforresource-get-openapi.md
- name: AWS Inspector API - Preview Agents
  x-api-slug: actionpreviewagents-get
  description: |-
    Previews the agents installed on the EC2 instances that are part of the specified
             assessment target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionpreviewagents-get-openapi.md
- name: AWS Inspector API - Register Cross Account Access Role
  x-api-slug: actionregistercrossaccountaccessrole-get
  description: |-
    Registers the IAM role that Amazon Inspector uses to list your EC2 instances at the
             start of the assessment run or when you call the.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionregistercrossaccountaccessrole-get-openapi.md
- name: AWS Inspector API - Remove Attributes From Findings
  x-api-slug: actionremoveattributesfromfindings-get
  description: |-
    Removes entire attributes (key and value pairs) from the findings that are specified
             by the ARNs of the findings where an attribute with the specified key exists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionremoveattributesfromfindings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionremoveattributesfromfindings-get-openapi.md
- name: AWS Inspector API - Set Tags For Resource
  x-api-slug: actionsettagsforresource-get
  description: |-
    Sets tags (key and value pairs) to the assessment template that is specified by the
             ARN of the assessment template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionsettagsforresource-get-openapi.md
- name: AWS Inspector API - Start Assessment Run
  x-api-slug: actionstartassessmentrun-get
  description: Starts the assessment run specified by the ARN of the assessment template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionstartassessmentrun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionstartassessmentrun-get-openapi.md
- name: AWS Inspector API - Stop Assessment Run
  x-api-slug: actionstopassessmentrun-get
  description: |-
    Stops the assessment run that is specified by the ARN of the assessment
             run.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionstopassessmentrun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionstopassessmentrun-get-openapi.md
- name: AWS Inspector API - Subscribe To Event
  x-api-slug: actionsubscribetoevent-get
  description: |-
    Enables the process of sending Amazon Simple Notification Service (SNS) notifications
             about a specified event to a specified SNS topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionsubscribetoevent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionsubscribetoevent-get-openapi.md
- name: AWS Inspector API - Unsubscribe From Event
  x-api-slug: actionunsubscribefromevent-get
  description: |-
    Disables the process of sending Amazon Simple Notification Service (SNS)
             notifications about a specified event to a specified SNS topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionunsubscribefromevent-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionunsubscribefromevent-get-openapi.md
- name: AWS Inspector API - Update Assessment Target
  x-api-slug: actionupdateassessmenttarget-get
  description: |-
    Updates the assessment target that is specified by the ARN of the assessment
             target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Amazon Web Services, Security, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-inspector/actionupdateassessmenttarget-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.identity.and.access.management.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.inspector.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/inspector/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/inspector/faqs/
- type: x-getting-started
  url: https://docs.aws.amazon.com/inspector/latest/userguide/inspector_quickstart.html
- type: x-partners
  url: https://aws.amazon.com/inspector/partners/
- type: x-pricing
  url: https://aws.amazon.com/inspector/pricing/
- type: x-testimonials
  url: https://aws.amazon.com/inspector/customers/
- type: x-website
  url: https://aws.amazon.com/inspector/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---