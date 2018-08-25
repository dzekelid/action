---
swagger: "2.0"
x-collection-name: AWS Database Migration Service
x-complete: 0
info:
  title: AWS Database Migration Service API Describe Certificates
  version: 1.0.0
  description: Provides a description of the certificate.
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
  /?Action=CreateReplicationTask:
    get:
      summary: Create Replication Task
      description: Creates a replication task using the specified parameters.
      operationId: createReplicationTask
      x-api-path-slug: actioncreatereplicationtask-get
      parameters:
      - in: query
        name: CdcStartTime
        description: The start time for the Change Data Capture (CDC) operation
        type: string
      - in: query
        name: MigrationType
        description: The migration type
        type: string
      - in: query
        name: ReplicationInstanceArn
        description: The Amazon Resource Name (ARN) of the replication instance
        type: string
      - in: query
        name: ReplicationTaskIdentifier
        description: The replication task identifier
        type: string
      - in: query
        name: ReplicationTaskSettings
        description: Settings for the task, such as target metadata settings
        type: string
      - in: query
        name: SourceEndpointArn
        description: The Amazon Resource Name (ARN) string that uniquely identifies
          the endpoint
        type: string
      - in: query
        name: TableMappings
        description: The path of the JSON file that contains the table mappings
        type: string
      - in: query
        name: Tags
        description: Tags to be added to the replication instance
        type: string
      - in: query
        name: TargetEndpointArn
        description: The Amazon Resource Name (ARN) string that uniquely identifies
          the endpoint
        type: string
      responses:
        200:
          description: OK
      tags:
      - Replication Tasks
  /?Action=DeleteCertificate:
    get:
      summary: Delete Certificate
      description: Deletes the specified certificate.
      operationId: deleteCertificate
      x-api-path-slug: actiondeletecertificate-get
      parameters:
      - in: query
        name: CertificateArn
        description: The Amazon Resource Name (ARN) of the deleted certificate
        type: string
      responses:
        200:
          description: OK
      tags:
      - Certificates
  /?Action=DeleteEndpoint:
    get:
      summary: Delete Endpoint
      description: Deletes the specified endpoint.
      operationId: deleteEndpoint
      x-api-path-slug: actiondeleteendpoint-get
      parameters:
      - in: query
        name: EndpointArn
        description: The Amazon Resource Name (ARN) string that uniquely identifies
          the endpoint
        type: string
      responses:
        200:
          description: OK
      tags:
      - Endpoints
  /?Action=DeleteReplicationInstance:
    get:
      summary: Delete Replication Instance
      description: Deletes the specified replication instance.
      operationId: deleteReplicationInstance
      x-api-path-slug: actiondeletereplicationinstance-get
      parameters:
      - in: query
        name: ReplicationInstanceArn
        description: The Amazon Resource Name (ARN) of the replication instance to
          be deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Replication Instances
  /?Action=DeleteReplicationSubnetGroup:
    get:
      summary: Delete Replication Subnet Group
      description: Deletes a subnet group.
      operationId: deleteReplicationSubnetGroup
      x-api-path-slug: actiondeletereplicationsubnetgroup-get
      parameters:
      - in: query
        name: ReplicationSubnetGroupIdentifier
        description: The subnet group name of the replication instance
        type: string
      responses:
        200:
          description: OK
      tags:
      - Replication Subnet Group
  /?Action=DeleteReplicationTask:
    get:
      summary: Delete Replication Task
      description: Deletes the specified replication task.
      operationId: deleteReplicationTask
      x-api-path-slug: actiondeletereplicationtask-get
      parameters:
      - in: query
        name: ReplicationTaskArn
        description: The Amazon Resource Name (ARN) of the replication task to be
          deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Replication Tasks
  /?Action=DescribeAccountAttributes:
    get:
      summary: Describe Account Attributes
      description: Lists all of the AWS DMS attributes for a customer account.
      operationId: describeAccountAttributes
      x-api-path-slug: actiondescribeaccountattributes-get
      parameters:
      - in: query
        name: AccountQuotas
        description: Account quota information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Account Attributes
  /?Action=DescribeCertificates:
    get:
      summary: Describe Certificates
      description: Provides a description of the certificate.
      operationId: describeCertificates
      x-api-path-slug: actiondescribecertificates-get
      parameters:
      - in: query
        name: Filters
        description: Filters applied to the certificate described in the form of key-value
          pairs
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous         request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Certificates
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