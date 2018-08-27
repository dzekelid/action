---
name: AWS Elastic MapReduce
x-slug: aws-elastic-mapreduce
description: Amazon EMR provides a managed Hadoop framework that makes it easy, fast,
  and cost-effective to process vast amounts of data across dynamically scalable Amazon
  EC2 instances. You can also run other popular distributed frameworks such as Apache
  Spark, HBase, Presto, and Flink in Amazon EMR, and interact with data in other AWS
  data stores such as Amazon S3 and Amazon DynamoDB.Amazon EMR securely and reliably
  handles a broad set of big data use cases, including log analysis, web indexing,
  data transformations (ETL), machine learning, financial analysis, scientific simulation,
  and bioinformatics.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Action
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Elastic MapReduce API - Add Instance Groups
  x-api-slug: actionaddinstancegroups-get
  description: Adds one or more instance groups to a running cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionaddinstancegroups-get-openapi.md
- name: AWS Elastic MapReduce API - Add Job Flow Steps
  x-api-slug: actionaddjobflowsteps-get
  description: AddJobFlowSteps adds new steps to a running job flow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionaddjobflowsteps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionaddjobflowsteps-get-openapi.md
- name: AWS Elastic MapReduce API - Add Tags
  x-api-slug: actionaddtags-get
  description: Adds tags to an Amazon EMR resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionaddtags-get-openapi.md
- name: AWS Elastic MapReduce API - Cancel Steps
  x-api-slug: actioncancelsteps-get
  description: Cancels a pending step or steps in a running cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actioncancelsteps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actioncancelsteps-get-openapi.md
- name: AWS Elastic MapReduce API - Create Security Configuration
  x-api-slug: actioncreatesecurityconfiguration-get
  description: Creates a security configuration, which is stored in the service and
    can be specified when a cluster is created.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actioncreatesecurityconfiguration-get-openapi.md
- name: AWS Elastic MapReduce API - Delete Security Configuration
  x-api-slug: actiondeletesecurityconfiguration-get
  description: Deletes a security configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actiondeletesecurityconfiguration-get-openapi.md
- name: AWS Elastic MapReduce API - Describe Cluster
  x-api-slug: actiondescribecluster-get
  description: Provides cluster-level details including status, hardware and software
    configuration, VPC settings, and so on.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actiondescribecluster-get-openapi.md
- name: AWS Elastic MapReduce API - Describe Job Flows
  x-api-slug: actiondescribejobflows-get
  description: This API is deprecated and will eventually be removed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actiondescribejobflows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actiondescribejobflows-get-openapi.md
- name: AWS Elastic MapReduce API - Describe Security Configuration
  x-api-slug: actiondescribesecurityconfiguration-get
  description: Provides the details of a security configuration by returning the configuration
    JSON.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actiondescribesecurityconfiguration-get-openapi.md
- name: AWS Elastic MapReduce API - Describe Step
  x-api-slug: actiondescribestep-get
  description: Provides more detail about the cluster step.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actiondescribestep-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actiondescribestep-get-openapi.md
- name: AWS Elastic MapReduce API - List Bootstrap Actions
  x-api-slug: actionlistbootstrapactions-get
  description: Provides information about the bootstrap actions associated with a
    cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionlistbootstrapactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionlistbootstrapactions-get-openapi.md
- name: AWS Elastic MapReduce API - List Clusters
  x-api-slug: actionlistclusters-get
  description: Provides the status of all clusters visible to this AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionlistclusters-get-openapi.md
- name: AWS Elastic MapReduce API - List Instance Groups
  x-api-slug: actionlistinstancegroups-get
  description: Provides all available details about the instance groups in a cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionlistinstancegroups-get-openapi.md
- name: AWS Elastic MapReduce API - List Instances
  x-api-slug: actionlistinstances-get
  description: "Provides information about the cluster instances that Amazon EMR provisions
    on behalf of a user \n         when it creates the cluster."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionlistinstances-get-openapi.md
- name: AWS Elastic MapReduce API - List Security Configurations
  x-api-slug: actionlistsecurityconfigurations-get
  description: Lists all the security configurations visible to this account, providing
    their creation dates and times, and their names.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionlistsecurityconfigurations-get-openapi.md
- name: AWS Elastic MapReduce API - List Steps
  x-api-slug: actionliststeps-get
  description: Provides a list of steps for the cluster in reverse order unless you
    specify stepIds with the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionliststeps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionliststeps-get-openapi.md
- name: AWS Elastic MapReduce API - Modify Instance Groups
  x-api-slug: actionmodifyinstancegroups-get
  description: ModifyInstanceGroups modifies the number of nodes and configuration
    settings of an instance group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionmodifyinstancegroups-get-openapi.md
- name: AWS Elastic MapReduce API - Put Auto Scaling Policy
  x-api-slug: actionputautoscalingpolicy-get
  description: Creates or updates an automatic scaling policy for a core instance
    group or task instance group in an Amazon EMR cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionputautoscalingpolicy-get-openapi.md
- name: AWS Elastic MapReduce API - Remove Auto Scaling Policy
  x-api-slug: actionremoveautoscalingpolicy-get
  description: Removes an automatic scaling policy from a specified instance group
    within an EMR cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionremoveautoscalingpolicy-get-openapi.md
- name: AWS Elastic MapReduce API - Remove Tags
  x-api-slug: actionremovetags-get
  description: Removes tags from an Amazon EMR resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionremovetags-get-openapi.md
- name: AWS Elastic MapReduce API - Run Job Flow
  x-api-slug: actionrunjobflow-get
  description: RunJobFlow creates and starts running a new job flow.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionrunjobflow-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionrunjobflow-get-openapi.md
- name: AWS Elastic MapReduce API - Set Termination Protection
  x-api-slug: actionsetterminationprotection-get
  description: SetTerminationProtection locks a job flow so the EC2 instances in the
    cluster cannot be terminated by user intervention, an API call, or in the event
    of a job-flow error.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionsetterminationprotection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionsetterminationprotection-get-openapi.md
- name: AWS Elastic MapReduce API - Set Visible To All Users
  x-api-slug: actionsetvisibletoallusers-get
  description: Sets whether all AWS Identity and Access Management (IAM) users under
    your account can access the specified job flows.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionsetvisibletoallusers-get-openapi.md
- name: AWS Elastic MapReduce API - Terminate Job Flows
  x-api-slug: actionterminatejobflows-get
  description: TerminateJobFlows shuts a list of job flows down.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonEMR.png
  humanURL: https://aws.amazon.com/emr/
  baseURL: :///
  tags: Amazon Web Services, Data, MapReduce, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionterminatejobflows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-elastic-mapreduce/actionterminatejobflows-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.elastic.load.balancing.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.elastic.mapreduce.stack.network
- type: x-article
  url: http://aws.amazon.com/articles/Elastic-MapReduce
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/ElasticMapReduce/latest/DeveloperGuide/emr-cli-reference.html
- type: x-faq
  url: https://aws.amazon.com/emr/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/emr/getting-started/
- type: x-partners
  url: https://aws.amazon.com/emr/partners/
- type: x-pricing
  url: https://aws.amazon.com/emr/pricing/
- type: x-documentation
  url: http://docs.aws.amazon.com/ElasticMapReduce/latest/API/
- type: x-website
  url: https://aws.amazon.com/emr/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---