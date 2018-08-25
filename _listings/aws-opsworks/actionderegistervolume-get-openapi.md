---
swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 0
info:
  title: AWS OpsWorks API Deregister Volume
  version: 1.0.0
  description: Deregisters an Amazon EBS volume.
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
  /?Action=CreateDeployment:
    get:
      summary: Create Deployment
      description: Runs deployment or stack commands.
      operationId: createDeployment
      x-api-path-slug: actioncreatedeployment-get
      parameters:
      - in: query
        name: AppId
        description: The app ID
        type: string
      - in: query
        name: Command
        description: A DeploymentCommand object that specifies the deployment command
          and any      associated arguments
        type: string
      - in: query
        name: Comment
        description: A user-defined comment
        type: string
      - in: query
        name: CustomJson
        description: A string that contains user-defined, custom JSON
        type: string
      - in: query
        name: InstanceIds
        description: The instance IDs for the deployment targets
        type: string
      - in: query
        name: LayerIds
        description: The layer IDs for the deployment targets
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deployment
  /?Action=CreateInstance:
    get:
      summary: Create Instance
      description: Creates an instance in a specified stack.
      operationId: createInstance
      x-api-path-slug: actioncreateinstance-get
      parameters:
      - in: query
        name: AgentVersion
        description: The default AWS OpsWorks Stacks agent version
        type: string
      - in: query
        name: AmiId
        description: A custom AMI ID to be used to create the instance
        type: string
      - in: query
        name: Architecture
        description: The instance architecture
        type: string
      - in: query
        name: AutoScalingType
        description: For load-based or time-based instances, the type
        type: string
      - in: query
        name: AvailabilityZone
        description: The instance Availability Zone
        type: string
      - in: query
        name: BlockDeviceMappings
        description: An array of BlockDeviceMapping objects that specify the instances
          block      devices
        type: string
      - in: query
        name: EbsOptimized
        description: Whether to create an Amazon EBS-optimized instance
        type: string
      - in: query
        name: Hostname
        description: The instance host name
        type: string
      - in: query
        name: InstallUpdatesOnBoot
        description: Whether to install operating system and package updates when
          the instance boots
        type: string
      - in: query
        name: InstanceType
        description: The instance type, such as t2
        type: string
      - in: query
        name: LayerIds
        description: An array that contains the instances layer IDs
        type: string
      - in: query
        name: Os
        description: The instances operating system, which must be set to one of the
          following
        type: string
      - in: query
        name: RootDeviceType
        description: The instance root device type
        type: string
      - in: query
        name: SshKeyName
        description: The instances Amazon EC2 key-pair name
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      - in: query
        name: SubnetId
        description: The ID of the instances subnet
        type: string
      - in: query
        name: Tenancy
        description: The instances tenancy option
        type: string
      - in: query
        name: VirtualizationType
        description: The instances virtualization type, paravirtual or hvm
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance
  /?Action=CreateLayer:
    get:
      summary: Create Layer
      description: Creates a layer.
      operationId: createLayer
      x-api-path-slug: actioncreatelayer-get
      parameters:
      - in: query
        name: Attributes
        description: One or more user-defined key-value pairs to be added to the stack
          attributes
        type: string
      - in: query
        name: AutoAssignElasticIps
        description: Whether to automatically assign an Elastic IP        address
          to the layers instances
        type: string
      - in: query
        name: AutoAssignPublicIps
        description: For stacks that are running in a VPC, whether to automatically
          assign a public IP address to      the layers instances
        type: string
      - in: query
        name: CustomInstanceProfileArn
        description: The ARN of an IAM profile to be used for the layers EC2 instances
        type: string
      - in: query
        name: CustomJson
        description: A JSON-formatted string containing custom stack configuration
          and deployment attributes     to be installed on the layers instances
        type: string
      - in: query
        name: CustomRecipes
        description: A LayerCustomRecipes object that specifies the layer custom recipes
        type: string
      - in: query
        name: CustomSecurityGroupIds
        description: An array containing the layer custom security group IDs
        type: string
      - in: query
        name: EnableAutoHealing
        description: Whether to disable auto healing for the layer
        type: string
      - in: query
        name: InstallUpdatesOnBoot
        description: Whether to install operating system and package updates when
          the instance boots
        type: string
      - in: query
        name: LifecycleEventConfiguration
        description: A LifeCycleEventConfiguration object that you can use to configure
          the Shutdown event to      specify an execution timeout and enable or disable
          Elastic Load Balancer connection      draining
        type: string
      - in: query
        name: Name
        description: The layer name, which is used by the console
        type: string
      - in: query
        name: Packages
        description: An array of Package objects that describes the layer packages
        type: string
      - in: query
        name: Shortname
        description: For custom layers only, use this parameter to specify the layers
          short name, which is used internally by AWS OpsWorks Stacks and by Chef
          recipes
        type: string
      - in: query
        name: StackId
        description: The layer stack ID
        type: string
      - in: query
        name: Type
        description: The layer type
        type: string
      - in: query
        name: UseEbsOptimizedInstances
        description: Whether to use Amazon EBS-optimized instances
        type: string
      - in: query
        name: VolumeConfigurations
        description: A VolumeConfigurations object that describes the layers Amazon
          EBS volumes
        type: string
      responses:
        200:
          description: OK
      tags:
      - Layer
  /?Action=CreateStack:
    get:
      summary: Create Stack
      description: Creates a new stack.
      operationId: createStack
      x-api-path-slug: actioncreatestack-get
      parameters:
      - in: query
        name: AgentVersion
        description: The default AWS OpsWorks Stacks agent version
        type: string
      - in: query
        name: Attributes
        description: One or more user-defined key-value pairs to be added to the stack
          attributes
        type: string
      - in: query
        name: ChefConfiguration
        description: A ChefConfiguration object that specifies whether to enable Berkshelf
          and the      Berkshelf version on Chef 11
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
        description: The stacks default Availability Zone, which must be in the specified
          region
        type: string
      - in: query
        name: DefaultInstanceProfileArn
        description: The Amazon Resource Name (ARN) of an IAM profile that is the
          default profile for all of the stacks EC2 instances
        type: string
      - in: query
        name: DefaultOs
        description: The stacks default operating system, which is installed on every
          instance unless you specify a different operating system when you create
          the instance
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
        description: The stacks host name theme, with spaces replaced by underscores
        type: string
      - in: query
        name: Name
        description: The stack name
        type: string
      - in: query
        name: Region
        description: The stacks AWS region, such as ap-south-1
        type: string
      - in: query
        name: ServiceRoleArn
        description: The stacks AWS Identity and Access Management (IAM) role, which
          allows AWS OpsWorks Stacks to work with AWS      resources on your behalf
        type: string
      - in: query
        name: UseCustomCookbooks
        description: Whether the stack uses custom cookbooks
        type: string
      - in: query
        name: UseOpsworksSecurityGroups
        description: Whether to associate the AWS OpsWorks Stacks built-in security
          groups with the stacks layers
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC that the stack is to be launched into
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stack
  /?Action=CreateUserProfile:
    get:
      summary: Create User Profile
      description: Creates a new user profile.
      operationId: createUserProfile
      x-api-path-slug: actioncreateuserprofile-get
      parameters:
      - in: query
        name: AllowSelfManagement
        description: Whether users can specify their own SSH public key through the
          My Settings page
        type: string
      - in: query
        name: IamUserArn
        description: The users IAM ARN; this can also be a federated users ARN
        type: string
      - in: query
        name: SshPublicKey
        description: The users public SSH key
        type: string
      - in: query
        name: SshUsername
        description: The users SSH user name
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Profile
  /?Action=DeleteApp:
    get:
      summary: Delete App
      description: Deletes a specified app.
      operationId: deleteApp
      x-api-path-slug: actiondeleteapp-get
      parameters:
      - in: query
        name: AppId
        description: The app ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - App
  /?Action=DeleteInstance:
    get:
      summary: Delete Instance
      description: Deletes a specified instance, which terminates the associated Amazon
        EC2 instance.
      operationId: deleteInstance
      x-api-path-slug: actiondeleteinstance-get
      parameters:
      - in: query
        name: DeleteElasticIp
        description: Whether to delete the instance Elastic IP address
        type: string
      - in: query
        name: DeleteVolumes
        description: Whether to delete the instances Amazon EBS volumes
        type: string
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance
  /?Action=DeleteLayer:
    get:
      summary: Delete Layer
      description: Deletes a specified layer.
      operationId: deleteLayer
      x-api-path-slug: actiondeletelayer-get
      parameters:
      - in: query
        name: LayerId
        description: The layer ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Layer
  /?Action=DeleteStack:
    get:
      summary: Delete Stack
      description: Deletes a specified stack.
      operationId: deleteStack
      x-api-path-slug: actiondeletestack-get
      parameters:
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stack
  /?Action=DeleteUserProfile:
    get:
      summary: Delete User Profile
      description: Deletes a user profile.
      operationId: deleteUserProfile
      x-api-path-slug: actiondeleteuserprofile-get
      parameters:
      - in: query
        name: IamUserArn
        description: The users IAM ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - User
      - Profile
  /?Action=DeregisterEcsCluster:
    get:
      summary: Deregister Ecs Cluster
      description: Deregisters a specified Amazon ECS cluster from a stack.
      operationId: deregisterEcsCluster
      x-api-path-slug: actionderegisterecscluster-get
      parameters:
      - in: query
        name: EcsClusterArn
        description: The clusters ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deregister
      - Ecs
      - Cluster
  /?Action=DeregisterElasticIp:
    get:
      summary: Deregister Elastic IP
      description: Deregisters a specified Elastic IP address.
      operationId: deregisterElasticIp
      x-api-path-slug: actionderegisterelasticip-get
      parameters:
      - in: query
        name: ElasticIp
        description: The Elastic IP address
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deregister
      - Elastic
      - IP Addresses
  /?Action=DeregisterInstance:
    get:
      summary: Deregister Instance
      description: Deregister a registered Amazon EC2 or on-premises instance.
      operationId: deregisterInstance
      x-api-path-slug: actionderegisterinstance-get
      parameters:
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deregister
      - Instance
  /?Action=DeregisterRdsDbInstance:
    get:
      summary: Deregister Rds Db Instance
      description: Deregisters an Amazon RDS instance.
      operationId: deregisterRdsDbInstance
      x-api-path-slug: actionderegisterrdsdbinstance-get
      parameters:
      - in: query
        name: RdsDbInstanceArn
        description: The Amazon RDS instances ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deregister
      - Rds
      - Db
      - Instance
  /?Action=DeregisterVolume:
    get:
      summary: Deregister Volume
      description: Deregisters an Amazon EBS volume.
      operationId: deregisterVolume
      x-api-path-slug: actionderegistervolume-get
      parameters:
      - in: query
        name: VolumeId
        description: The AWS OpsWorks Stacks volume ID, which is the GUID that AWS
          OpsWorks Stacks assigned to the instance when you registered the volume
          with the stack, not the Amazon EC2 volume ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deregister
      - Volume
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