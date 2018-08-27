---
swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 0
info:
  title: AWS OpsWorks API Create App
  version: 1.0.0
  description: Creates an app for a specified stack.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AssignInstance:
    get:
      summary: Assign Instance
      description: Assign a registered instance to a layer.
      operationId: assignInstance
      x-api-path-slug: actionassigninstance-get
      parameters:
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      - in: query
        name: LayerIds
        description: The layer ID, which must correspond to a custom layer
        type: string
      responses:
        200:
          description: OK
      tags:
      - Assign
      - Instance
  /?Action=AssignVolume:
    get:
      summary: Assign Volume
      description: Assigns one of the stack's registered Amazon EBS volumes to a specified
        instance.
      operationId: assignVolume
      x-api-path-slug: actionassignvolume-get
      parameters:
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      - in: query
        name: VolumeId
        description: The volume ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Assign
      - Volume
  /?Action=AssociateElasticIp:
    get:
      summary: Associate Elastic IP
      description: Associates one of the stack's registered Elastic IP addresses with
        a specified instance.
      operationId: associateElasticIp
      x-api-path-slug: actionassociateelasticip-get
      parameters:
      - in: query
        name: ElasticIp
        description: The Elastic IP address
        type: string
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Associate
      - Elastic
      - IP Addresses
  /?Action=AttachElasticLoadBalancer:
    get:
      summary: Attach Elastic Load Balancer
      description: Attaches an Elastic Load Balancing load balancer to a specified
        layer.
      operationId: attachElasticLoadBalancer
      x-api-path-slug: actionattachelasticloadbalancer-get
      parameters:
      - in: query
        name: ElasticLoadBalancerName
        description: The Elastic Load Balancing instances name
        type: string
      - in: query
        name: LayerId
        description: The ID of the layer that the Elastic Load Balancing instance
          is to be attached to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attach
      - Elastic
      - Load
      - Balancer
  /?Action=CloneStack:
    get:
      summary: Clone Stack
      description: Creates a clone of a specified stack.
      operationId: cloneStack
      x-api-path-slug: actionclonestack-get
      parameters:
      - in: query
        name: AgentVersion
        description: The default AWS OpsWorks Stacks agent version
        type: string
      - in: query
        name: Attributes
        description: A list of stack attributes and values as key/value pairs to be
          added to the cloned stack
        type: string
      - in: query
        name: ChefConfiguration
        description: A ChefConfiguration object that specifies whether to enable Berkshelf
          and the      Berkshelf version on Chef 11
        type: string
      - in: query
        name: CloneAppIds
        description: A list of source stack app IDs to be included in the cloned stack
        type: string
      - in: query
        name: ClonePermissions
        description: Whether to clone the source stacks permissions
        type: string
      - in: query
        name: ConfigurationManager
        description: The configuration manager
        type: string
      - in: query
        name: CustomCookbooksSource
        description: Contains the information required to retrieve an app or cookbook
          from a repository
        type: string
      - in: query
        name: CustomJson
        description: A string that contains user-defined, custom JSON
        type: string
      - in: query
        name: DefaultAvailabilityZone
        description: The cloned stacks default Availability Zone, which must be in
          the specified region
        type: string
      - in: query
        name: DefaultInstanceProfileArn
        description: The Amazon Resource Name (ARN) of an IAM profile that is the
          default profile for all of the stacks EC2 instances
        type: string
      - in: query
        name: DefaultOs
        description: The stacks operating system, which must be set to one of the
          following
        type: string
      - in: query
        name: DefaultRootDeviceType
        description: The default root device type
        type: string
      - in: query
        name: DefaultSshKeyName
        description: A default Amazon EC2 key pair name
        type: string
      - in: query
        name: DefaultSubnetId
        description: The stacks default VPC subnet ID
        type: string
      - in: query
        name: HostnameTheme
        description: The stacks host name theme, with spaces are replaced by underscores
        type: string
      - in: query
        name: Name
        description: The cloned stack name
        type: string
      - in: query
        name: Region
        description: The cloned stack AWS region, such as ap-northeast-2
        type: string
      - in: query
        name: ServiceRoleArn
        description: The stack AWS Identity and Access Management (IAM) role, which
          allows AWS OpsWorks Stacks to work with AWS      resources on your behalf
        type: string
      - in: query
        name: SourceStackId
        description: The source stack ID
        type: string
      - in: query
        name: UseCustomCookbooks
        description: Whether to use custom cookbooks
        type: string
      - in: query
        name: UseOpsworksSecurityGroups
        description: Whether to associate the AWS OpsWorks Stacks built-in security
          groups with the stacks layers
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC that the cloned stack is to be launched into
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clone
      - Stack
  /?Action=CreateApp:
    get:
      summary: Create App
      description: Creates an app for a specified stack.
      operationId: createApp
      x-api-path-slug: actioncreateapp-get
      parameters:
      - in: query
        name: AppSource
        description: A Source object that specifies the app repository
        type: string
      - in: query
        name: Attributes
        description: One or more user-defined key/value pairs to be added to the stack
          attributes
        type: string
      - in: query
        name: DataSources
        description: The apps data source
        type: string
      - in: query
        name: Description
        description: A description of the app
        type: string
      - in: query
        name: Domains
        description: The app virtual host settings, with multiple domains separated
          by commas
        type: string
      - in: query
        name: EnableSsl
        description: Whether to enable SSL for the app
        type: string
      - in: query
        name: Environment
        description: An array of EnvironmentVariable objects that specify environment
          variables to be      associated with the app
        type: string
      - in: query
        name: Name
        description: The app name
        type: string
      - in: query
        name: Shortname
        description: The apps short name
        type: string
      - in: query
        name: SslConfiguration
        description: An SslConfiguration object with the SSL configuration
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      - in: query
        name: Type
        description: The app type
        type: string
      responses:
        200:
          description: OK
      tags:
      - App
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