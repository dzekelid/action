---
swagger: "2.0"
x-collection-name: AWS EC2 Container Service
x-complete: 0
info:
  title: Amazon EC2 Container Service API Describe Services
  version: 1.0.0
  description: Describes the specified services running in your cluster.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateCluster:
    get:
      summary: Create Cluster
      description: Creates a new Amazon ECS cluster.
      operationId: createCluster
      x-api-path-slug: actioncreatecluster-get
      parameters:
      - in: query
        name: clusterName
        description: The name of your cluster
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=CreateService:
    get:
      summary: Create Service
      description: Runs and maintains a desired number of tasks from a specified task
        definition.
      operationId: createService
      x-api-path-slug: actioncreateservice-get
      parameters:
      - in: query
        name: clientToken
        description: Unique, case-sensitive identifier you provide to ensure the idempotency
          of the            request
        type: string
      - in: query
        name: cluster
        description: The short name or full Amazon Resource Name (ARN) of the cluster
          on which to run your service
        type: string
      - in: query
        name: deploymentConfiguration
        description: Optional deployment parameters that control how many tasks run
          during the            deployment and the ordering of stopping and starting
          tasks
        type: string
      - in: query
        name: desiredCount
        description: The number of instantiations of the specified task definition
          to place and keep            running on your cluster
        type: string
      - in: query
        name: loadBalancers
        description: A load balancer object representing the load balancer to use
          with your service
        type: string
      - in: query
        name: placementConstraints
        description: An array of placement constraint objects to use for tasks in
          your service
        type: string
      - in: query
        name: placementStrategy
        description: The placement strategy objects to use for tasks in your service
        type: string
      - in: query
        name: role
        description: The name or full Amazon Resource Name (ARN) of the IAM role that
          allows Amazon ECS to make calls to your            load balancer on your
          behalf
        type: string
      - in: query
        name: serviceName
        description: The name of your service
        type: string
      - in: query
        name: taskDefinition
        description: The family and revision (family:revision) or            full
          Amazon Resource Name (ARN) of the task definition to run in your service
        type: string
      responses:
        200:
          description: OK
      tags:
      - Services
  /?Action=DeleteAttributes:
    get:
      summary: Delete Attributes
      description: Deletes one or more custom attributes from an Amazon ECS resource.
      operationId: deleteAttributes
      x-api-path-slug: actiondeleteattributes-get
      parameters:
      - in: query
        name: attributes
        description: The attributes to delete from your resource
        type: string
      - in: query
        name: cluster
        description: The short name or full Amazon Resource Name (ARN) of the cluster
          that contains the resource to apply            attributes
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attributes
  /?Action=DeleteCluster:
    get:
      summary: Delete Cluster
      description: Deletes the specified cluster.
      operationId: deleteCluster
      x-api-path-slug: actiondeletecluster-get
      parameters:
      - in: query
        name: cluster
        description: The short name or full Amazon Resource Name (ARN) of the cluster
          to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=DeleteService:
    get:
      summary: Delete Service
      description: Deletes a specified service within a cluster.
      operationId: deleteService
      x-api-path-slug: actiondeleteservice-get
      parameters:
      - in: query
        name: cluster
        description: The name of the cluster that hosts the service to delete
        type: string
      - in: query
        name: service
        description: The name of the service to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Services
  /?Action=DeregisterContainerInstance:
    get:
      summary: Deregister Container Instance
      description: Deregisters an Amazon ECS container instance from the specified
        cluster.
      operationId: deregisterContainerInstance
      x-api-path-slug: actionderegistercontainerinstance-get
      parameters:
      - in: query
        name: cluster
        description: The short name or full Amazon Resource Name (ARN) of the cluster
          that hosts the container instance            to deregister
        type: string
      - in: query
        name: containerInstance
        description: The container instance ID or full Amazon Resource Name (ARN)
          of the container instance to            deregister
        type: string
      - in: query
        name: force
        description: Forces the deregistration of the container instance
        type: string
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Instances
  /?Action=DeregisterTaskDefinition:
    get:
      summary: Deregister Task Definition
      description: Deregisters the specified task definition by family and revision.
      operationId: deregisterTaskDefinition
      x-api-path-slug: actionderegistertaskdefinition-get
      parameters:
      - in: query
        name: taskDefinition
        description: The family and revision (family:revision) or            full
          Amazon Resource Name (ARN) of the task definition to deregister
        type: string
      responses:
        200:
          description: OK
      tags:
      - Task Definitions
  /?Action=DescribeClusters:
    get:
      summary: Describe Clusters
      description: Describes one or more of your clusters.
      operationId: describeClusters
      x-api-path-slug: actiondescribeclusters-get
      parameters:
      - in: query
        name: clusters
        description: A space-separated list of up to 100 cluster names or full cluster
          Amazon Resource Name (ARN)            entries
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=DescribeContainerInstances:
    get:
      summary: Describe Container Instances
      description: Describes Amazon EC2 Container Service container instances.
      operationId: describeContainerInstances
      x-api-path-slug: actiondescribecontainerinstances-get
      parameters:
      - in: query
        name: cluster
        description: The short name or full Amazon Resource Name (ARN) of the cluster
          that hosts the container instances            to describe
        type: string
      - in: query
        name: containerInstances
        description: A space-separated list of container instance IDs or full Amazon
          Resource Name (ARN)            entries
        type: string
      responses:
        200:
          description: OK
      tags:
      - Containers
      - Instances
  /?Action=DescribeServices:
    get:
      summary: Describe Services
      description: Describes the specified services running in your cluster.
      operationId: describeServices
      x-api-path-slug: actiondescribeservices-get
      parameters:
      - in: query
        name: cluster
        description: The name of the cluster that hosts the service to describe
        type: string
      - in: query
        name: services
        description: A list of services to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Services
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