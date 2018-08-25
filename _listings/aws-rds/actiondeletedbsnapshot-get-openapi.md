---
swagger: "2.0"
x-collection-name: AWS RDS
x-complete: 0
info:
  title: Amazon RDS API Delete D B Snapshot
  version: 1.0.0
  description: Deletes a DBSnapshot.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddRoleToDBCluster:
    get:
      summary: Add Role To D B Cluster
      description: Associates an Identity and Access Management (IAM) role from an
        Aurora DB cluster.
      operationId: addroletodbcluster
      x-api-path-slug: actionaddroletodbcluster-get
      parameters:
      - in: query
        name: DBClusterIdentifier
        description: The name of the DB cluster to associate the IAM role with
        type: string
      - in: query
        name: RoleArn
        description: The Amazon Resource Name (ARN) of the IAM role to associate with
          the Aurora DB cluster, for example            arn:aws:iam::123456789012:role/AuroraAccessRole
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=AddSourceIdentifierToSubscription:
    get:
      summary: Add Source Identifier To Subscription
      description: Adds a source identifier to an existing RDS event notification
        subscription.
      operationId: addsourceidentifiertosubscription
      x-api-path-slug: actionaddsourceidentifiertosubscription-get
      parameters:
      - in: query
        name: SourceIdentifier
        description: The identifier of the event source to be added
        type: string
      - in: query
        name: SubscriptionName
        description: The name of the RDS event notification subscription you want
          to add a source identifier to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subscriptions
  /?Action=AddTagsToResource:
    get:
      summary: Add Tags To Resource
      description: Adds metadata tags to an Amazon RDS resource.
      operationId: addtagstoresource
      x-api-path-slug: actionaddtagstoresource-get
      parameters:
      - in: query
        name: ResourceName
        description: The Amazon RDS resource the tags will be added to
        type: string
      - in: query
        name: Tags.Tag.N
        description: The tags to be assigned to the Amazon RDS resource
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags
  /?Action=ApplyPendingMaintenanceAction:
    get:
      summary: Apply Pending Maintenance Action
      description: Applies a pending maintenance action to a resource (for example,
        to a DB instance).
      operationId: applypendingmaintenanceaction
      x-api-path-slug: actionapplypendingmaintenanceaction-get
      parameters:
      - in: query
        name: ApplyAction
        description: The pending maintenance action to apply to this resource
        type: string
      - in: query
        name: OptInType
        description: A value that specifies the type of opt-in request, or undoes
          an opt-in request
        type: string
      - in: query
        name: ResourceIdentifier
        description: The RDS Amazon Resource Name (ARN) of the resource that the       pending
          maintenance action applies to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Maintenance Actions
  /?Action=AuthorizeDBSecurityGroupIngress:
    get:
      summary: Authorize D B Security Group Ingress
      description: Enables ingress to a DBSecurityGroup using one of two forms of
        authorization.
      operationId: authorizedbsecuritygroupingress
      x-api-path-slug: actionauthorizedbsecuritygroupingress-get
      parameters:
      - in: query
        name: CIDRIP
        description: The IP range to authorize
        type: string
      - in: query
        name: DBSecurityGroupName
        description: The name of the DB security group to add authorization to
        type: string
      - in: query
        name: EC2SecurityGroupId
        description: Id of the EC2 security group to authorize
        type: string
      - in: query
        name: EC2SecurityGroupName
        description: Name of the EC2 security group to authorize
        type: string
      - in: query
        name: EC2SecurityGroupOwnerId
        description: AWS account number of the owner of the EC2 security group        specified
          in the EC2SecurityGroupName parameter
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Groups
  /?Action=CopyDBClusterParameterGroup:
    get:
      summary: Copy D B Cluster Parameter Group
      description: Copies the specified DB cluster parameter group.
      operationId: copydbclusterparametergroup
      x-api-path-slug: actioncopydbclusterparametergroup-get
      parameters:
      - in: query
        name: SourceDBClusterParameterGroupIdentifier
        description: The identifier or Amazon Resource Name (ARN) for the source DB
          cluster parameter group
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      - in: query
        name: TargetDBClusterParameterGroupDescription
        description: A description for the copied DB cluster parameter group
        type: string
      - in: query
        name: TargetDBClusterParameterGroupIdentifier
        description: The identifier for the copied DB cluster parameter group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Parameter Groups
  /?Action=CopyDBClusterSnapshot:
    get:
      summary: Copy D B Cluster Snapshot
      description: Creates a snapshot of a DB cluster.
      operationId: copydbclustersnapshot
      x-api-path-slug: actioncopydbclustersnapshot-get
      parameters:
      - in: query
        name: SourceDBClusterSnapshotIdentifier
        description: The identifier of the DB cluster snapshot to copy
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      - in: query
        name: TargetDBClusterSnapshotIdentifier
        description: The identifier of the new DB cluster snapshot to create from
          the source DB cluster snapshot
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Snapshots
  /?Action=CopyDBParameterGroup:
    get:
      summary: Copy D B Parameter Group
      description: Copies the specified DB parameter group.
      operationId: copydbparametergroup
      x-api-path-slug: actioncopydbparametergroup-get
      parameters:
      - in: query
        name: SourceDBParameterGroupIdentifier
        description: The identifier or ARN for the source DB parameter group
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      - in: query
        name: TargetDBParameterGroupDescription
        description: A description for the copied DB parameter group
        type: string
      - in: query
        name: TargetDBParameterGroupIdentifier
        description: The identifier for the copied DB parameter group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameter Groups
  /?Action=CopyDBSnapshot:
    get:
      summary: Copy D B Snapshot
      description: Copies the specified DB snapshot.
      operationId: copydbsnapshot
      x-api-path-slug: actioncopydbsnapshot-get
      parameters:
      - in: query
        name: CopyTags
        description: True to copy all tags from the source DB snapshot to the target
          DB snapshot; otherwise false
        type: string
      - in: query
        name: KmsKeyId
        description: The AWS KMS key ID for an encrypted DB snapshot
        type: string
      - in: query
        name: PreSignedUrl
        description: The URL that contains a Signature Version 4 signed request for
          the CopyDBSnapshot API action in the AWS region that contains the             source
          DB snapshot to copy
        type: string
      - in: query
        name: SourceDBSnapshotIdentifier
        description: The identifier for the source DB snapshot
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      - in: query
        name: TargetDBSnapshotIdentifier
        description: The identifier for the copied snapshot
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
  /?Action=CopyOptionGroup:
    get:
      summary: Copy Option Group
      description: Copies the specified option group.
      operationId: copyoptiongroup
      x-api-path-slug: actioncopyoptiongroup-get
      parameters:
      - in: query
        name: SourceOptionGroupIdentifier
        description: The identifier or ARN for the source option group
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      - in: query
        name: TargetOptionGroupDescription
        description: The description for the copied option group
        type: string
      - in: query
        name: TargetOptionGroupIdentifier
        description: The identifier for the copied option group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Option Groups
  /?Action=CreateDBCluster:
    get:
      summary: Create D B Cluster
      description: Creates a new Amazon Aurora DB cluster.
      operationId: createdbcluster
      x-api-path-slug: actioncreatedbcluster-get
      parameters:
      - in: query
        name: AvailabilityZones.AvailabilityZone.N
        description: A list of EC2 Availability Zones that instances in the DB cluster
          can be created in
        type: string
      - in: query
        name: BackupRetentionPeriod
        description: The number of days for which automated backups are retained
        type: string
      - in: query
        name: CharacterSetName
        description: A value that indicates that the DB cluster should be associated
          with the specified CharacterSet
        type: string
      - in: query
        name: DatabaseName
        description: The name for your database of up to 8 alpha-numeric characters
        type: string
      - in: query
        name: DBClusterIdentifier
        description: The DB cluster identifier
        type: string
      - in: query
        name: DBClusterParameterGroupName
        description: The name of the DB cluster parameter group to associate            with
          this DB cluster
        type: string
      - in: query
        name: DBSubnetGroupName
        description: A DB subnet group to associate with this DB cluster
        type: string
      - in: query
        name: Engine
        description: The name of the database engine to be used for this DB cluster
        type: string
      - in: query
        name: EngineVersion
        description: The version number of the database engine to use
        type: string
      - in: query
        name: KmsKeyId
        description: The KMS key identifier for an encrypted DB cluster
        type: string
      - in: query
        name: MasterUsername
        description: The name of the master user for the DB cluster
        type: string
      - in: query
        name: MasterUserPassword
        description: The password for the master database user
        type: string
      - in: query
        name: OptionGroupName
        description: A value that indicates that the DB cluster should be associated
          with the specified option group
        type: string
      - in: query
        name: Port
        description: The port number on which the instances in the DB cluster accept
          connections
        type: string
      - in: query
        name: PreferredBackupWindow
        description: The daily time range during which automated backups are created        if
          automated backups are enabled        using the BackupRetentionPeriod parameter
        type: string
      - in: query
        name: PreferredMaintenanceWindow
        description: The weekly time range during which system maintenance can occur,
          in Universal Coordinated Time (UTC)
        type: string
      - in: query
        name: ReplicationSourceIdentifier
        description: The Amazon Resource Name (ARN) of the source DB cluster if this
          DB cluster is created as a Read Replica
        type: string
      - in: query
        name: StorageEncrypted
        description: Specifies whether the DB cluster is encrypted
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      - in: query
        name: VpcSecurityGroupIds.VpcSecurityGroupId.N
        description: A list of EC2 VPC security groups to associate with this DB cluster
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=CreateDBClusterParameterGroup:
    get:
      summary: Create D B Cluster Parameter Group
      description: Creates a new DB cluster parameter group.
      operationId: createdbclusterparametergroup
      x-api-path-slug: actioncreatedbclusterparametergroup-get
      parameters:
      - in: query
        name: DBClusterParameterGroupName
        description: The name of the DB cluster parameter group
        type: string
      - in: query
        name: DBParameterGroupFamily
        description: The DB cluster parameter group family name
        type: string
      - in: query
        name: Description
        description: The description for the DB cluster parameter group
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Parameter Groups
  /?Action=CreateDBClusterSnapshot:
    get:
      summary: Create D B Cluster Snapshot
      description: Creates a snapshot of a DB cluster.
      operationId: createdbclustersnapshot
      x-api-path-slug: actioncreatedbclustersnapshot-get
      parameters:
      - in: query
        name: DBClusterIdentifier
        description: The identifier of the DB cluster to create a snapshot for
        type: string
      - in: query
        name: DBClusterSnapshotIdentifier
        description: The identifier of the DB cluster snapshot
        type: string
      - in: query
        name: Tags.Tag.N
        description: The tags to be assigned to the DB cluster snapshot
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Snapshots
  /?Action=CreateDBInstance:
    get:
      summary: Create D B Instance
      description: Creates a new DB instance.
      operationId: createdbinstance
      x-api-path-slug: actioncreatedbinstance-get
      parameters:
      - in: query
        name: AllocatedStorage
        description: The amount of storage (in gigabytes) to be initially allocated
          for the database instance
        type: string
      - in: query
        name: AutoMinorVersionUpgrade
        description: Indicates that minor engine upgrades will be applied automatically
          to the DB instance during the maintenance window
        type: string
      - in: query
        name: AvailabilityZone
        description: The EC2 Availability Zone that the database instance will be
          created in
        type: string
      - in: query
        name: BackupRetentionPeriod
        description: The number of days for which automated backups are retained
        type: string
      - in: query
        name: CharacterSetName
        description: For supported engines, indicates that the DB instance should
          be associated with the specified CharacterSet
        type: string
      - in: query
        name: CopyTagsToSnapshot
        description: True to copy all tags from the DB instance to snapshots of the
          DB instance; otherwise false
        type: string
      - in: query
        name: DBClusterIdentifier
        description: The identifier of the DB cluster that the instance will belong
          to
        type: string
      - in: query
        name: DBInstanceClass
        description: The compute and memory capacity of the DB instance
        type: string
      - in: query
        name: DBInstanceIdentifier
        description: The DB instance identifier
        type: string
      - in: query
        name: DBName
        description: The meaning of this parameter differs according to the database
          engine you use
        type: string
      - in: query
        name: DBParameterGroupName
        description: The name of the DB parameter group to associate with this DB
          instance
        type: string
      - in: query
        name: DBSecurityGroups.DBSecurityGroupName.N
        description: A list of DB security groups to associate with this DB instance
        type: string
      - in: query
        name: DBSubnetGroupName
        description: A DB subnet group to associate with this DB instance
        type: string
      - in: query
        name: Domain
        description: Specify the Active Directory Domain to create the instance in
        type: string
      - in: query
        name: DomainIAMRoleName
        description: Specify the name of the IAM role to be used when making API calls
          to the Directory Service
        type: string
      - in: query
        name: Engine
        description: The name of the database engine to be used for this instance
        type: string
      - in: query
        name: EngineVersion
        description: The version number of the database engine to use
        type: string
      - in: query
        name: Iops
        description: The amount of Provisioned IOPS (input/output operations per second)
          to be initially allocated for the DB instance
        type: string
      - in: query
        name: KmsKeyId
        description: The KMS key identifier for an encrypted DB instance
        type: string
      - in: query
        name: LicenseModel
        description: License model information for this DB instance
        type: string
      - in: query
        name: MasterUsername
        description: The name of master user for the client DB instance
        type: string
      - in: query
        name: MasterUserPassword
        description: The password for the master database user
        type: string
      - in: query
        name: MonitoringInterval
        description: The interval, in seconds, between points when Enhanced Monitoring
          metrics are collected for the DB instance
        type: string
      - in: query
        name: MonitoringRoleArn
        description: The ARN for the IAM role that permits RDS to send enhanced monitoring
          metrics to CloudWatch Logs
        type: string
      - in: query
        name: MultiAZ
        description: Specifies if the DB instance is a Multi-AZ deployment
        type: string
      - in: query
        name: OptionGroupName
        description: Indicates that the DB instance should be associated with the
          specified option group
        type: string
      - in: query
        name: Port
        description: The port number on which the database accepts connections
        type: string
      - in: query
        name: PreferredBackupWindow
        description: The daily time range during which automated backups are created        if
          automated backups are enabled,        using the BackupRetentionPeriod parameter
        type: string
      - in: query
        name: PreferredMaintenanceWindow
        description: The weekly time range during which system maintenance can occur,
          in Universal Coordinated Time (UTC)
        type: string
      - in: query
        name: PromotionTier
        description: A value that specifies the order in which an Aurora Replica is
          promoted to the primary instance       after a failure of the existing primary
          instance
        type: string
      - in: query
        name: PubliclyAccessible
        description: Specifies the accessibility options for the DB instance
        type: string
      - in: query
        name: StorageEncrypted
        description: Specifies whether the DB instance is encrypted
        type: string
      - in: query
        name: StorageType
        description: Specifies the storage type to be associated with the DB instance
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      - in: query
        name: TdeCredentialArn
        description: The ARN from the Key Store with which to associate the instance
          for TDE encryption
        type: string
      - in: query
        name: TdeCredentialPassword
        description: The password for the given ARN from the Key Store in order to
          access the device
        type: string
      - in: query
        name: Timezone
        description: The time zone of the DB instance
        type: string
      - in: query
        name: VpcSecurityGroupIds.VpcSecurityGroupId.N
        description: A list of EC2 VPC security groups to associate with this DB instance
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances
  /?Action=CreateDBInstanceReadReplica:
    get:
      summary: Create D B Instance Read Replica
      description: Creates a DB instance for a DB instance running MySQL, MariaDB,
        or PostgreSQL that acts as a Read Replica of a source DB instance.
      operationId: createdbinstancereadreplica
      x-api-path-slug: actioncreatedbinstancereadreplica-get
      parameters:
      - in: query
        name: AutoMinorVersionUpgrade
        description: Indicates that minor engine upgrades will be applied automatically
          to the Read Replica during the maintenance window
        type: string
      - in: query
        name: AvailabilityZone
        description: The Amazon EC2 Availability Zone that the Read Replica will be
          created in
        type: string
      - in: query
        name: CopyTagsToSnapshot
        description: True to copy all tags from the Read Replica to snapshots of the
          Read Replica; otherwise false
        type: string
      - in: query
        name: DBInstanceClass
        description: The compute and memory capacity of the Read Replica
        type: string
      - in: query
        name: DBInstanceIdentifier
        description: The DB instance identifier of the Read Replica
        type: string
      - in: query
        name: DBSubnetGroupName
        description: Specifies a DB subnet group for the DB instance
        type: string
      - in: query
        name: Iops
        description: The amount of Provisioned IOPS (input/output operations per second)
          to be initially allocated for the DB instance
        type: string
      - in: query
        name: MonitoringInterval
        description: The interval, in seconds, between points when Enhanced Monitoring
          metrics are collected for the Read Replica
        type: string
      - in: query
        name: MonitoringRoleArn
        description: The ARN for the IAM role that permits RDS to send enhanced monitoring
          metrics to CloudWatch Logs
        type: string
      - in: query
        name: OptionGroupName
        description: The option group the DB instance will be associated with
        type: string
      - in: query
        name: Port
        description: The port number that the DB instance uses for connections
        type: string
      - in: query
        name: PubliclyAccessible
        description: Specifies the accessibility options for the DB instance
        type: string
      - in: query
        name: SourceDBInstanceIdentifier
        description: The identifier of the DB instance that will act as the source
          for the Read Replica
        type: string
      - in: query
        name: StorageType
        description: Specifies the storage type to be associated with the Read Replica
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances
  /?Action=CreateDBParameterGroup:
    get:
      summary: Create D B Parameter Group
      description: Creates a new DB parameter group.
      operationId: createdbparametergroup
      x-api-path-slug: actioncreatedbparametergroup-get
      parameters:
      - in: query
        name: DBParameterGroupFamily
        description: The DB parameter group family name
        type: string
      - in: query
        name: DBParameterGroupName
        description: The name of the DB parameter group
        type: string
      - in: query
        name: Description
        description: The description for the DB parameter group
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameter Groups
  /?Action=CreateDBSecurityGroup:
    get:
      summary: Create D B Security Group
      description: Creates a new DB security group.
      operationId: createdbsecuritygroup
      x-api-path-slug: actioncreatedbsecuritygroup-get
      parameters:
      - in: query
        name: DBSecurityGroupDescription
        description: The description for the DB security group
        type: string
      - in: query
        name: DBSecurityGroupName
        description: The name for the DB security group
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Groups
  /?Action=CreateDBSnapshot:
    get:
      summary: Create D B Snapshot
      description: Creates a DBSnapshot.
      operationId: createdbsnapshot
      x-api-path-slug: actioncreatedbsnapshot-get
      parameters:
      - in: query
        name: DBInstanceIdentifier
        description: The DB instance identifier
        type: string
      - in: query
        name: DBSnapshotIdentifier
        description: The identifier for the DB snapshot
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
  /?Action=CreateDBSubnetGroup:
    get:
      summary: Create D B Subnet Group
      description: Creates a new DB subnet group.
      operationId: createdbsubnetgroup
      x-api-path-slug: actioncreatedbsubnetgroup-get
      parameters:
      - in: query
        name: DBSubnetGroupDescription
        description: The description for the DB subnet group
        type: string
      - in: query
        name: DBSubnetGroupName
        description: The name for the DB subnet group
        type: string
      - in: query
        name: SubnetIds.SubnetIdentifier.N
        description: The EC2 Subnet IDs for the DB subnet group
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subnet Groups
  /?Action=CreateEventSubscription:
    get:
      summary: Create Event Subscription
      description: Creates an RDS event notification subscription.
      operationId: createeventsubscription
      x-api-path-slug: actioncreateeventsubscription-get
      parameters:
      - in: query
        name: Enabled
        description: A Boolean value; set to true to activate the subscription, set
          to false to create the subscription but not active it
        type: string
      - in: query
        name: EventCategories.EventCategory.N
        description: A list of event categories for a SourceType that you want to
          subscribe to
        type: string
      - in: query
        name: SnsTopicArn
        description: The Amazon Resource Name (ARN) of the SNS topic created for event
          notification
        type: string
      - in: query
        name: SourceIds.SourceId.N
        description: The list of identifiers of the event sources for which events
          will be returned
        type: string
      - in: query
        name: SourceType
        description: The type of source that will be generating the events
        type: string
      - in: query
        name: SubscriptionName
        description: The name of the subscription
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event Subscriptions
  /?Action=CreateOptionGroup:
    get:
      summary: Create Option Group
      description: Creates a new option group.
      operationId: createoptiongroup
      x-api-path-slug: actioncreateoptiongroup-get
      parameters:
      - in: query
        name: EngineName
        description: Specifies the name of the engine that this option group should
          be associated with
        type: string
      - in: query
        name: MajorEngineVersion
        description: Specifies the major version of the engine that this option group
          should be associated with
        type: string
      - in: query
        name: OptionGroupDescription
        description: The description of the option group
        type: string
      - in: query
        name: OptionGroupName
        description: Specifies the name of the option group to be created
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - Option Groups
  /?Action=DeleteDBCluster:
    get:
      summary: Delete D B Cluster
      description: The DeleteDBCluster action deletes a previously provisioned DB
        cluster.
      operationId: deletedbcluster
      x-api-path-slug: actiondeletedbcluster-get
      parameters:
      - in: query
        name: DBClusterIdentifier
        description: The DB cluster identifier for the DB cluster to be deleted
        type: string
      - in: query
        name: FinalDBSnapshotIdentifier
        description: The DB cluster snapshot identifier of the new DB cluster snapshot
          created when SkipFinalSnapshot      is set to false
        type: string
      - in: query
        name: SkipFinalSnapshot
        description: Determines whether a final DB cluster snapshot is created before
          the DB cluster is deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=DeleteDBClusterParameterGroup:
    get:
      summary: Delete D B Cluster Parameter Group
      description: Deletes a specified DB cluster parameter group.
      operationId: deletedbclusterparametergroup
      x-api-path-slug: actiondeletedbclusterparametergroup-get
      parameters:
      - in: query
        name: DBClusterParameterGroupName
        description: The name of the DB cluster parameter group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Parameter Groups
  /?Action=DeleteDBClusterSnapshot:
    get:
      summary: Delete D B Cluster Snapshot
      description: Deletes a DB cluster snapshot.
      operationId: deletedbclustersnapshot
      x-api-path-slug: actiondeletedbclustersnapshot-get
      parameters:
      - in: query
        name: DBClusterSnapshotIdentifier
        description: The identifier of the DB cluster snapshot to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Snapshots
  /?Action=DeleteDBInstance:
    get:
      summary: Delete D B Instance
      description: The DeleteDBInstance action deletes a previously provisioned DB
        instance.
      operationId: deletedbinstance
      x-api-path-slug: actiondeletedbinstance-get
      parameters:
      - in: query
        name: DBInstanceIdentifier
        description: The DB instance identifier for the DB instance to be deleted
        type: string
      - in: query
        name: FinalDBSnapshotIdentifier
        description: The DBSnapshotIdentifier of the new DBSnapshot created when SkipFinalSnapshot        is
          set to false
        type: string
      - in: query
        name: SkipFinalSnapshot
        description: Determines whether a final DB snapshot is created before the
          DB instance is deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances
  /?Action=DeleteDBParameterGroup:
    get:
      summary: Delete D B Parameter Group
      description: Deletes a specified DBParameterGroup.
      operationId: deletedbparametergroup
      x-api-path-slug: actiondeletedbparametergroup-get
      parameters:
      - in: query
        name: DBParameterGroupName
        description: The name of the DB parameter group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameter Groups
  /?Action=DeleteDBSecurityGroup:
    get:
      summary: Delete D B Security Group
      description: Deletes a DB security group.
      operationId: deletedbsecuritygroup
      x-api-path-slug: actiondeletedbsecuritygroup-get
      parameters:
      - in: query
        name: DBSecurityGroupName
        description: The name of the DB security group to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Groups
  /?Action=DeleteDBSnapshot:
    get:
      summary: Delete D B Snapshot
      description: Deletes a DBSnapshot.
      operationId: deletedbsnapshot
      x-api-path-slug: actiondeletedbsnapshot-get
      parameters:
      - in: query
        name: DBSnapshotIdentifier
        description: The DBSnapshot identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
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