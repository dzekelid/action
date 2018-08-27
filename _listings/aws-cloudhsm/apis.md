---
name: AWS CloudHSM
x-slug: aws-cloudhsm
description: The AWS CloudHSM service helps you meet corporate, contractual and regulatory
  compliance requirements for data security by using dedicated Hardware Security Module
  (HSM) appliances within the AWS cloud. With CloudHSM, you control the encryption
  keys and cryptographic operations performed by the HSM.AWS and AWS Marketplace partners
  offer a variety of solutions for protecting sensitive data within the AWS platform,
  but for applications and data subject to rigorous contractual or regulatory requirements
  for managing cryptographic keys, additional protection is sometimes necessary. Until
  now, your only option was to store the sensitive data (or the encryption keys protecting
  the sensitive data) in your on-premises datacenters. Unfortunately, this either
  prevented you from migrating these applications to the cloud or significantly slowed
  their performance. The AWS CloudHSM service allows you to protect your encryption
  keys within HSMs designed and validated to government standards for secure key management.
  You can securely generate, store, and manage the cryptographic keys used for data
  encryption such that they are accessible only by you. AWS CloudHSM helps you comply
  with strict key management requirements without sacrificing application performance.The
  AWS CloudHSM service works with Amazon Virtual Private Cloud (VPC). CloudHSM instances
  are provisioned inside your VPC with an IP address that you specify, providing simple
  and private network connectivity to your Amazon Elastic Compute Cloud (EC2) instances.
  Placing CloudHSM instances near your EC2 instances decreases network latency, which
  can improve application performance. AWS provides dedicated and exclusive (single
  tenant) access to CloudHSM instances, isolated from other AWS customers. Available
  in multiple Regions and Availability Zones (AZs), AWS CloudHSM allows you to add
  secure and durable key storage to your applications.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Action
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/apis.md
specificationVersion: "0.14"
apis:
- name: AWS CloudHSM API - Add Tags To Resource
  x-api-slug: actionaddtagstoresource-get
  description: Adds or overwrites one or more tags for the specified AWS CloudHSM
    resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actionaddtagstoresource-get-openapi.md
- name: AWS CloudHSM API - Create Hapg
  x-api-slug: actioncreatehapg-get
  description: Creates a high-availability partition group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actioncreatehapg-get-openapi.md
- name: AWS CloudHSM API - Create HSM
  x-api-slug: actioncreatehsm-get
  description: Creates an uninitialized HSM instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actioncreatehsm-get-openapi.md
- name: AWS CloudHSM API - Create Luna Client
  x-api-slug: actioncreatelunaclient-get
  description: Creates an HSM client.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actioncreatelunaclient-get-openapi.md
- name: AWS CloudHSM API - Delete HAPG
  x-api-slug: actiondeletehapg-get
  description: Deletes a high-availability partition group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actiondeletehapg-get-openapi.md
- name: AWS CloudHSM API - Delete HSM
  x-api-slug: actiondeletehsm-get
  description: Deletes an HSM.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actiondeletehsm-get-openapi.md
- name: AWS CloudHSM API - Delete Luna Client
  x-api-slug: actiondeletelunaclient-get
  description: Deletes a client.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actiondeletelunaclient-get-openapi.md
- name: AWS CloudHSM API - Describe HAPG
  x-api-slug: actiondescribehapg-get
  description: Retrieves information about a high-availability partition group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actiondescribehapg-get-openapi.md
- name: AWS CloudHSM API - Describe HSM
  x-api-slug: actiondescribehsm-get
  description: Retrieves information about an HSM.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actiondescribehsm-get-openapi.md
- name: AWS CloudHSM API - Describe Luna Client
  x-api-slug: actiondescribelunaclient-get
  description: Retrieves information about an HSM client.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actiondescribelunaclient-get-openapi.md
- name: AWS CloudHSM API - Get Config
  x-api-slug: actiongetconfig-get
  description: |-
    Gets the configuration files necessary to connect to all high availability partition
          groups the client is associated with.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actiongetconfig-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actiongetconfig-get-openapi.md
- name: AWS CloudHSM API - List Available Zones
  x-api-slug: actionlistavailablezones-get
  description: Lists the Availability Zones that have available AWS CloudHSM capacity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actionlistavailablezones-get-openapi.md
- name: AWS CloudHSM API - List HAPG
  x-api-slug: actionlisthapgs-get
  description: Lists the high-availability partition groups for the account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actionlisthapgs-get-openapi.md
- name: AWS CloudHSM API - List HSM
  x-api-slug: actionlisthsms-get
  description: |-
    Retrieves the identifiers of all of the HSMs provisioned for the current
          customer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actionlisthsms-get-openapi.md
- name: AWS CloudHSM API - List Luna Clients
  x-api-slug: actionlistlunaclients-get
  description: Lists all of the clients.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actionlistlunaclients-get-openapi.md
- name: AWS CloudHSM API - List Tags For Resource
  x-api-slug: actionlisttagsforresource-get
  description: Returns a list of all tags for the specified AWS CloudHSM resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actionlisttagsforresource-get-openapi.md
- name: AWS CloudHSM API - Modify HAPG
  x-api-slug: actionmodifyhapg-get
  description: Modifies an existing high-availability partition group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actionmodifyhapg-get-openapi.md
- name: AWS CloudHSM API - Modify HSM
  x-api-slug: actionmodifyhsm-get
  description: Modifies an HSM.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actionmodifyhsm-get-openapi.md
- name: AWS CloudHSM API - Modify Luna Client
  x-api-slug: actionmodifylunaclient-get
  description: Modifies the certificate used by the client.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actionmodifylunaclient-get-openapi.md
- name: AWS CloudHSM API - Remove Tags From Resource
  x-api-slug: actionremovetagsfromresource-get
  description: Removes one or more tags from the specified AWS CloudHSM resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSCloudHSM.png
  humanURL: https://aws.amazon.com/cloudhsm/
  baseURL: :///
  tags: Amazon Web Services, Contracts, Regulations, Management, Encryption, Stack
    Network, API Service Provider, API Service Provider, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-cloudhsm/actionremovetagsfromresource-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.cloudfront.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.cloudhsm.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/cloudhsm/latest/dg/
- type: x-faq
  url: https://aws.amazon.com/cloudhsm/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=156
- type: x-getting-started
  url: https://aws.amazon.com/cloudhsm/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/cloudhsm/pricing/
- type: x-release-notes
  url: http://aws.amazon.com/releasenotes/AWS-CloudHSM/
- type: x-website
  url: https://aws.amazon.com/cloudhsm/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---