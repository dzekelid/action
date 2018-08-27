---
name: AWS EC2 Container Service
x-slug: aws-ec2-container-service
description: Amazon EC2 Container Service (ECS) is a highly scalable, high performance
  container management service that supports Docker containers and allows you to easily
  run applications on a managed cluster of Amazon EC2 instances. Amazon ECS eliminates
  the need for you to install, operate, and scale your own cluster management infrastructure.
  With simple API calls, you can launch and stop Docker-enabled applications, query
  the complete state of your cluster, and access many familiar features like security
  groups, Elastic Load Balancing, EBS volumes, and IAM roles. You can use Amazon ECS
  to schedule the placement of containers across your cluster based on your resource
  needs and availability requirements. You can also integrate your own scheduler or
  third-party schedulers to meet business or application specific requirements.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Action
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS EC2 Container Service API - Create Cluster
  x-api-slug: actioncreatecluster-get
  description: Creates a new Amazon ECS cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actioncreatecluster-get-openapi.md
- name: AWS EC2 Container Service API - Create Service
  x-api-slug: actioncreateservice-get
  description: Runs and maintains a desired number of tasks from a specified task
    definition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actioncreateservice-get-openapi.md
- name: AWS EC2 Container Service API - Delete Attributes
  x-api-slug: actiondeleteattributes-get
  description: Deletes one or more custom attributes from an Amazon ECS resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actiondeleteattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actiondeleteattributes-get-openapi.md
- name: AWS EC2 Container Service API - Delete Cluster
  x-api-slug: actiondeletecluster-get
  description: Deletes the specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actiondeletecluster-get-openapi.md
- name: AWS EC2 Container Service API - Delete Service
  x-api-slug: actiondeleteservice-get
  description: Deletes a specified service within a cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actiondeleteservice-get-openapi.md
- name: AWS EC2 Container Service API - Deregister Container Instance
  x-api-slug: actionderegistercontainerinstance-get
  description: Deregisters an Amazon ECS container instance from the specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionderegistercontainerinstance-get-openapi.md
- name: AWS EC2 Container Service API - Deregister Task Definition
  x-api-slug: actionderegistertaskdefinition-get
  description: Deregisters the specified task definition by family and revision.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionderegistertaskdefinition-get-openapi.md
- name: AWS EC2 Container Service API - Describe Clusters
  x-api-slug: actiondescribeclusters-get
  description: Describes one or more of your clusters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actiondescribeclusters-get-openapi.md
- name: AWS EC2 Container Service API - Describe Container Instances
  x-api-slug: actiondescribecontainerinstances-get
  description: Describes Amazon EC2 Container Service container instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actiondescribecontainerinstances-get-openapi.md
- name: AWS EC2 Container Service API - Describe Services
  x-api-slug: actiondescribeservices-get
  description: Describes the specified services running in your cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actiondescribeservices-get-openapi.md
- name: AWS EC2 Container Service API - Describe Task Definition
  x-api-slug: actiondescribetaskdefinition-get
  description: Describes a task definition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actiondescribetaskdefinition-get-openapi.md
- name: AWS EC2 Container Service API - Describe Tasks
  x-api-slug: actiondescribetasks-get
  description: Describes a specified task or tasks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actiondescribetasks-get-openapi.md
- name: AWS EC2 Container Service API - Discover Poll Endpoint
  x-api-slug: actiondiscoverpollendpoint-get
  description: This action is only used by the Amazon EC2 Container Service agent,
    and it is not intended for use outside of the agent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actiondiscoverpollendpoint-get-openapi.md
- name: AWS EC2 Container Service API - List Attributes
  x-api-slug: actionlistattributes-get
  description: |-
    Lists the attributes for Amazon ECS resources within a specified target type and
                cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionlistattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionlistattributes-get-openapi.md
- name: AWS EC2 Container Service API - List Clusters
  x-api-slug: actionlistclusters-get
  description: Returns a list of existing clusters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionlistclusters-get-openapi.md
- name: AWS EC2 Container Service API - List Container Instances
  x-api-slug: actionlistcontainerinstances-get
  description: Returns a list of container instances in a specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionlistcontainerinstances-get-openapi.md
- name: AWS EC2 Container Service API - List Services
  x-api-slug: actionlistservices-get
  description: Lists the services that are running in a specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionlistservices-get-openapi.md
- name: AWS EC2 Container Service API - List Task Definition Families
  x-api-slug: actionlisttaskdefinitionfamilies-get
  description: |-
    Returns a list of task definition families that are registered to your account
                (which may include task definition families that no longer have any ACTIVE
                task definition revisions).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionlisttaskdefinitionfamilies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionlisttaskdefinitionfamilies-get-openapi.md
- name: AWS EC2 Container Service API - List Task Definitions
  x-api-slug: actionlisttaskdefinitions-get
  description: Returns a list of task definitions that are registered to your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionlisttaskdefinitions-get-openapi.md
- name: AWS EC2 Container Service API - List Tasks
  x-api-slug: actionlisttasks-get
  description: Returns a list of tasks for a specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionlisttasks-get-openapi.md
- name: AWS EC2 Container Service API - Put Attributes
  x-api-slug: actionputattributes-get
  description: Create or update an attribute on an Amazon ECS resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionputattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionputattributes-get-openapi.md
- name: AWS EC2 Container Service API - Register Container Instance
  x-api-slug: actionregistercontainerinstance-get
  description: Deregisters an Amazon ECS container instance from the specified cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionregistercontainerinstance-get-openapi.md
- name: AWS EC2 Container Service API - Register Task Definition
  x-api-slug: actionregistertaskdefinition-get
  description: |-
    Registers a new task definition from the supplied family and
                    containerDefinitions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionregistertaskdefinition-get-openapi.md
- name: AWS EC2 Container Service API - Run Task
  x-api-slug: actionruntask-get
  description: Starts a new task using the specified task definition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionruntask-get-openapi.md
- name: AWS EC2 Container Service API - Start Task
  x-api-slug: actionstarttask-get
  description: |-
    Starts a new task from the specified task definition on the specified container
                instance or instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionstarttask-get-openapi.md
- name: AWS EC2 Container Service API - Stop Task
  x-api-slug: actionstoptask-get
  description: Stops a running task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionstoptask-get-openapi.md
- name: AWS EC2 Container Service API - Submit Container State Change
  x-api-slug: actionsubmitcontainerstatechange-get
  description: This action is only used by the Amazon EC2 Container Service agent,
    and it is not intended for use outside of the agent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionsubmitcontainerstatechange-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionsubmitcontainerstatechange-get-openapi.md
- name: AWS EC2 Container Service API - Submit Task State Change
  x-api-slug: actionsubmittaskstatechange-get
  description: This action is only used by the Amazon EC2 Container Service agent,
    and it is not intended for use outside of the agent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionsubmittaskstatechange-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionsubmittaskstatechange-get-openapi.md
- name: AWS EC2 Container Service API - Update Container Agent
  x-api-slug: actionupdatecontaineragent-get
  description: Updates the Amazon ECS container agent on a specified container instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionupdatecontaineragent-get-openapi.md
- name: AWS EC2 Container Service API - Update Service
  x-api-slug: actionupdateservice-get
  description: |-
    Modifies the desired count, deployment configuration, or task definition used in a
                service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonECS.png
  humanURL: https://aws.amazon.com/ecs/
  baseURL: :///
  tags: Amazon Web Services, Containers, Stack Network, API Service Provider, API
    Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-ec2-container-service/actionupdateservice-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.ec2.container.registry.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.ec2.container.service.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/AmazonECS/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/ecs/faqs/
- type: x-getting-started
  url: https://portal.aws.amazon.com/gp/aws/developer/registration/index.html
- type: x-pricing
  url: https://aws.amazon.com/ecs/pricing/
- type: x-website
  url: https://aws.amazon.com/ecs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---