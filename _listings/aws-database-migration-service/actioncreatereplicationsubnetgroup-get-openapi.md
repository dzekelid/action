---
swagger: "2.0"
x-collection-name: AWS Database Migration Service
x-complete: 0
info:
  title: AWS Database Migration Service API Create Replication Subnet Group
  version: 1.0.0
  description: Creates a replication subnet group given a list of the subnet IDs in
    a VPC.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddTagsToResource:
    get:
      summary: Add Tags To Resource
      description: Adds metadata tags to a DMS resource, including replication instance,
        endpoint, security group, and migration task.
      operationId: addTagsToResource
      x-api-path-slug: actionaddtagstoresource-get
      parameters:
      - in: query
        name: ResourceArn
        description: The Amazon Resource Name (ARN) of the AWS DMS resource the tag
          is to be added to
        type: string
      - in: query
        name: Tags
        description: The tag to be assigned to the DMS resource
        type: string
      responses:
        200:
          description: OK
      tags:
      - Resource Tags
  /?Action=CreateEndpoint:
    get:
      summary: Create Endpoint
      description: Creates an endpoint using the provided settings.
      operationId: createEndpoint
      x-api-path-slug: actioncreateendpoint-get
      parameters:
      - in: query
        name: CertificateArn
        description: The Amazon Resource Number (ARN) for the certificate
        type: string
      - in: query
        name: DatabaseName
        description: The name of the endpoint database
        type: string
      - in: query
        name: EndpointIdentifier
        description: The database endpoint identifier
        type: string
      - in: query
        name: EndpointType
        description: The type of endpoint
        type: string
      - in: query
        name: EngineName
        description: The type of engine for the endpoint
        type: string
      - in: query
        name: ExtraConnectionAttributes
        description: Additional attributes associated with the connection
        type: string
      - in: query
        name: KmsKeyId
        description: The KMS key identifier that will be used to encrypt the connection
          parameters
        type: string
      - in: query
        name: Password
        description: The password to be used to login to the endpoint database
        type: string
      - in: query
        name: Port
        description: The port used by the endpoint database
        type: string
      - in: query
        name: ServerName
        description: The name of the server where the endpoint database resides
        type: string
      - in: query
        name: SslMode
        description: The SSL mode to use for the SSL connection
        type: string
      - in: query
        name: Tags
        description: Tags to be added to the endpoint
        type: string
      - in: query
        name: Username
        description: The user name to be used to login to the endpoint database
        type: string
      responses:
        200:
          description: OK
      tags:
      - Endpoints
  /?Action=CreateReplicationInstance:
    get:
      summary: Create Replication Instance
      description: Creates the replication instance using the specified parameters.
      operationId: createReplicationInstance
      x-api-path-slug: actioncreatereplicationinstance-get
      parameters:
      - in: query
        name: AllocatedStorage
        description: The amount of storage (in gigabytes) to be initially allocated
          for the replication instance
        type: string
      - in: query
        name: AutoMinorVersionUpgrade
        description: Indicates that minor engine upgrades will be applied automatically
          to the replication instance during the maintenance window
        type: string
      - in: query
        name: AvailabilityZone
        description: The EC2 Availability Zone that the replication instance will
          be created in
        type: string
      - in: query
        name: EngineVersion
        description: The engine version number of the replication instance
        type: string
      - in: query
        name: KmsKeyId
        description: The KMS key identifier that will be used to encrypt the content
          on the replication instance
        type: string
      - in: query
        name: MultiAZ
        description: Specifies if the replication instance is a Multi-AZ deployment
        type: string
      - in: query
        name: PreferredMaintenanceWindow
        description: The weekly time range during which system maintenance can occur,
          in Universal Coordinated Time (UTC)
        type: string
      - in: query
        name: PubliclyAccessible
        description: Specifies the accessibility options for the replication instance
        type: string
      - in: query
        name: ReplicationInstanceClass
        description: The compute and memory capacity of the replication instance as
          specified by the replication instance class
        type: string
      - in: query
        name: ReplicationInstanceIdentifier
        description: The replication instance identifier
        type: string
      - in: query
        name: ReplicationSubnetGroupIdentifier
        description: A subnet group to associate with the replication instance
        type: string
      - in: query
        name: Tags
        description: Tags to be associated with the replication instance
        type: string
      - in: query
        name: VpcSecurityGroupIds
        description: Specifies the VPC security group to be used with the replication
          instance
        type: string
      responses:
        200:
          description: OK
      tags:
      - Replication Instances
  /?Action=CreateReplicationSubnetGroup:
    get:
      summary: Create Replication Subnet Group
      description: Creates a replication subnet group given a list of the subnet IDs
        in a VPC.
      operationId: createReplicationSubnetGroup
      x-api-path-slug: actioncreatereplicationsubnetgroup-get
      parameters:
      - in: query
        name: ReplicationSubnetGroupDescription
        description: The description for the subnet group
        type: string
      - in: query
        name: ReplicationSubnetGroupIdentifier
        description: The name for the replication subnet group
        type: string
      - in: query
        name: SubnetIds
        description: The EC2 subnet IDs for the subnet group
        type: string
      - in: query
        name: Tags
        description: The tag to be assigned to the subnet group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Replication Subnet Group
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