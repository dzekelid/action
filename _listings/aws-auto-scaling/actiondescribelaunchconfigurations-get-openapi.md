---
swagger: "2.0"
x-collection-name: AWS Auto Scaling
x-complete: 0
info:
  title: AWS Auto Scaling API Describe Launch Configurations
  version: 1.0.0
  description: Describes one or more launch configurations.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AttachInstances:
    get:
      summary: Attach Instances
      description: Attaches one or more EC2 instances to the specified Auto Scaling
        group.
      operationId: attachInstances
      x-api-path-slug: actionattachinstances-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the group
        type: string
      - in: query
        name: InstanceIds.member.N
        description: One or more instance IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Instance
  /?Action=AttachLoadBalancers:
    get:
      summary: Attach Load Balancers
      description: Attaches one or more Classic load balancers to the specified Auto
        Scaling group.
      operationId: attachLoadBalancers
      x-api-path-slug: actionattachloadbalancers-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the group
        type: string
      - in: query
        name: LoadBalancerNames.member.N
        description: One or more load balancer names
        type: string
      responses:
        200:
          description: OK
      tags:
      - Load Balancers
  /?Action=AttachLoadBalancerTargetGroups:
    get:
      summary: Attach Load Balancer Target Groups
      description: Attaches one or more target groups to the specified Auto Scaling
        group.
      operationId: attachLoadBalancerTargetGroups
      x-api-path-slug: actionattachloadbalancertargetgroups-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the Auto Scaling group
        type: string
      - in: query
        name: TargetGroupARNs.member.N
        description: The Amazon Resource Names (ARN) of the target groups
        type: string
      responses:
        200:
          description: OK
      tags:
      - Load Balancers
  /?Action=CompleteLifecycleAction:
    get:
      summary: Complete Lifecycle Action
      description: Completes the lifecycle action for the specified token or instance
        with the specified result.
      operationId: completeLifecycleAction
      x-api-path-slug: actioncompletelifecycleaction-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the group for the lifecycle hook
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: LifecycleActionResult
        description: The action for the group to take
        type: string
      - in: query
        name: LifecycleActionToken
        description: A universally unique identifier (UUID) that identifies a specific
          lifecycle action associated with an instance
        type: string
      - in: query
        name: LifecycleHookName
        description: The name of the lifecycle hook
        type: string
      responses:
        200:
          description: OK
      tags:
      - Life Cycle
  /?Action=CreateAutoScalingGroup:
    get:
      summary: Create Auto Scaling Group
      description: Creates an Auto Scaling group with the specified name and attributes.
      operationId: createAutoScalingGroup
      x-api-path-slug: actioncreateautoscalinggroup-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the group
        type: string
      - in: query
        name: AvailabilityZones.member.N
        description: One or more Availability Zones for the group
        type: string
      - in: query
        name: DefaultCooldown
        description: The amount of time, in seconds, after a scaling activity completes
          before another scaling activity can start
        type: string
      - in: query
        name: DesiredCapacity
        description: The number of EC2 instances that should be running in the group
        type: string
      - in: query
        name: HealthCheckGracePeriod
        description: The amount of time, in seconds, that Auto Scaling waits before
          checking the health status of an EC2 instance that has come into service
        type: string
      - in: query
        name: HealthCheckType
        description: The service to use for the health checks
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance used to create a launch configuration
          for the group
        type: string
      - in: query
        name: LaunchConfigurationName
        description: The name of the launch configuration
        type: string
      - in: query
        name: LoadBalancerNames.member.N
        description: One or more Classic load balancers
        type: string
      - in: query
        name: MaxSize
        description: The maximum size of the group
        type: string
      - in: query
        name: MinSize
        description: The minimum size of the group
        type: string
      - in: query
        name: NewInstancesProtectedFromScaleIn
        description: Indicates whether newly launched instances are protected from
          termination by Auto Scaling when scaling in
        type: string
      - in: query
        name: PlacementGroup
        description: The name of the placement group into which youll launch your
          instances, if any
        type: string
      - in: query
        name: Tags.member.N
        description: One or more tags
        type: string
      - in: query
        name: TargetGroupARNs.member.N
        description: The Amazon Resource Names (ARN) of the target groups
        type: string
      - in: query
        name: TerminationPolicies.member.N
        description: One or more termination policies used to select the instance
          to terminate
        type: string
      - in: query
        name: VPCZoneIdentifier
        description: A comma-separated list of subnet identifiers for your virtual
          private cloud (VPC)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Auto Scaling Groups
  /?Action=CreateLaunchConfiguration:
    get:
      summary: Create Launch Configuration
      description: Creates a launch configuration.
      operationId: createLaunchConfiguration
      x-api-path-slug: actioncreatelaunchconfiguration-get
      parameters:
      - in: query
        name: AssociatePublicIpAddress
        description: Used for groups that launch instances into a virtual private
          cloud (VPC)
        type: string
      - in: query
        name: BlockDeviceMappings.member.N
        description: One or more mappings that specify how block devices are exposed
          to the instance
        type: string
      - in: query
        name: ClassicLinkVPCId
        description: The ID of a ClassicLink-enabled VPC to link your EC2-Classic
          instances to
        type: string
      - in: query
        name: ClassicLinkVPCSecurityGroups.member.N
        description: The IDs of one or more security groups for the specified ClassicLink-enabled
          VPC
        type: string
      - in: query
        name: EbsOptimized
        description: Indicates whether the instance is optimized for Amazon EBS I/O
        type: string
      - in: query
        name: IamInstanceProfile
        description: The name or the Amazon Resource Name (ARN) of the instance profile
          associated with the IAM role for the instance
        type: string
      - in: query
        name: ImageId
        description: The ID of the Amazon Machine Image (AMI) to use to launch your
          EC2 instances
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance to use to create the launch configuration
        type: string
      - in: query
        name: InstanceMonitoring
        description: Enables detailed monitoring (true) or basic monitoring (false)
          for the Auto Scaling instances
        type: string
      - in: query
        name: InstanceType
        description: The instance type of the EC2 instance
        type: string
      - in: query
        name: KernelId
        description: The ID of the kernel associated with the AMI
        type: string
      - in: query
        name: KeyName
        description: The name of the key pair
        type: string
      - in: query
        name: LaunchConfigurationName
        description: The name of the launch configuration
        type: string
      - in: query
        name: PlacementTenancy
        description: The tenancy of the instance
        type: string
      - in: query
        name: RamdiskId
        description: The ID of the RAM disk associated with the AMI
        type: string
      - in: query
        name: SecurityGroups.member.N
        description: One or more security groups with which to associate the instances
        type: string
      - in: query
        name: SpotPrice
        description: The maximum hourly price to be paid for any Spot Instance launched
          to fulfill the request
        type: string
      - in: query
        name: UserData
        description: The user data to make available to the launched EC2 instances
        type: string
      responses:
        200:
          description: OK
      tags:
      - Launch
  /?Action=CreateOrUpdateTags:
    get:
      summary: Create Or Update Tags
      description: Creates or updates tags for the specified Auto Scaling group.
      operationId: createOrUpdateTags
      x-api-path-slug: actioncreateorupdatetags-get
      parameters:
      - in: query
        name: Tags.member.N
        description: One or more tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags
  /?Action=DeleteAutoScalingGroup:
    get:
      summary: Delete Auto Scaling Group
      description: Deletes the specified Auto Scaling group.
      operationId: deleteAutoScalingGroup
      x-api-path-slug: actiondeleteautoscalinggroup-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the group to delete
        type: string
      - in: query
        name: ForceDelete
        description: Specifies that the group will be deleted along with all instances
          associated with the group, without waiting for all instances to be terminated
        type: string
      responses:
        200:
          description: OK
      tags:
      - Auto Scaling Groups
  /?Action=DeleteLaunchConfiguration:
    get:
      summary: Delete Launch Configuration
      description: Deletes the specified launch configuration.
      operationId: deleteLaunchConfiguration
      x-api-path-slug: actiondeletelaunchconfiguration-get
      parameters:
      - in: query
        name: LaunchConfigurationName
        description: The name of the launch configuration
        type: string
      responses:
        200:
          description: OK
      tags:
      - Launch
  /?Action=DeleteLifecycleHook:
    get:
      summary: Delete Lifecycle Hook
      description: Deletes the specified lifecycle hook.
      operationId: deleteLifecycleHook
      x-api-path-slug: actiondeletelifecyclehook-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the Auto Scaling group for the lifecycle hook
        type: string
      - in: query
        name: LifecycleHookName
        description: The name of the lifecycle hook
        type: string
      responses:
        200:
          description: OK
      tags:
      - Life Cycle
  /?Action=DeleteNotificationConfiguration:
    get:
      summary: Delete Notification Configuration
      description: Deletes the specified notification.
      operationId: deleteNotificationConfiguration
      x-api-path-slug: actiondeletenotificationconfiguration-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the Auto Scaling group
        type: string
      - in: query
        name: TopicARN
        description: The Amazon Resource Name (ARN) of the Amazon Simple Notification
          Service (SNS) topic
        type: string
      responses:
        200:
          description: OK
      tags:
      - Notifications
  /?Action=DeletePolicy:
    get:
      summary: Delete Policy
      description: Deletes the specified Auto Scaling policy.
      operationId: deletePolicy
      x-api-path-slug: actiondeletepolicy-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the Auto Scaling group
        type: string
      - in: query
        name: PolicyName
        description: The name or Amazon Resource Name (ARN) of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
  /?Action=DeleteScheduledAction:
    get:
      summary: Delete Scheduled Action
      description: Deletes the specified scheduled action.
      operationId: deleteScheduledAction
      x-api-path-slug: actiondeletescheduledaction-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the Auto Scaling group
        type: string
      - in: query
        name: ScheduledActionName
        description: The name of the action to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Scheduled Action
  /?Action=DeleteTags:
    get:
      summary: Delete Tags
      description: Deletes the specified tags.
      operationId: deleteTags
      x-api-path-slug: actiondeletetags-get
      parameters:
      - in: query
        name: Tags.member.N
        description: One or more tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags
  /?Action=DescribeAccountLimits:
    get:
      summary: Describe Account Limits
      description: Describes the current Auto Scaling resource limits for your AWS
        account.
      operationId: describeAccountLimits
      x-api-path-slug: actiondescribeaccountlimits-get
      parameters:
      - in: query
        name: MaxNumberOfAutoScalingGroups
        description: The maximum number of groups allowed for your AWS account
        type: string
      - in: query
        name: MaxNumberOfLaunchConfigurations
        description: The maximum number of launch configurations allowed for your
          AWS account
        type: string
      - in: query
        name: NumberOfAutoScalingGroups
        description: The current number of groups for your AWS account
        type: string
      - in: query
        name: NumberOfLaunchConfigurations
        description: The current number of launch configurations for your AWS account
        type: string
      responses:
        200:
          description: OK
      tags:
      - Account Limits
  /?Action=DescribeAdjustmentTypes:
    get:
      summary: Describe Adjustment Types
      description: Describes the policy adjustment types for use with.
      operationId: describeAdjustmentTypes
      x-api-path-slug: actiondescribeadjustmenttypes-get
      parameters:
      - in: query
        name: AdjustmentTypes.member.N
        description: The policy adjustment types
        type: string
      responses:
        200:
          description: OK
      tags:
      - Adjustment Types
  /?Action=DescribeAutoScalingGroups:
    get:
      summary: Describe Auto Scaling Groups
      description: Describes one or more Auto Scaling groups.
      operationId: describeAutoScalingGroups
      x-api-path-slug: actiondescribeautoscalinggroups-get
      parameters:
      - in: query
        name: AutoScalingGroupNames.member.N
        description: The group names
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Auto Scaling Groups
  /?Action=DescribeAutoScalingInstances:
    get:
      summary: Describe Auto Scaling Instances
      description: Describes one or more Auto Scaling instances.
      operationId: describeAutoScalingInstances
      x-api-path-slug: actiondescribeautoscalinginstances-get
      parameters:
      - in: query
        name: InstanceIds.member.N
        description: The instances to describe; up to 50 instance IDs
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Auto Scaling Instances
  /?Action=DescribeAutoScalingNotificationTypes:
    get:
      summary: Describe Auto Scaling Notification Types
      description: Describes the notification types that are supported by Auto Scaling.
      operationId: describeAutoScalingNotificationTypes
      x-api-path-slug: actiondescribeautoscalingnotificationtypes-get
      parameters:
      - in: query
        name: AutoScalingNotificationTypes.member.N
        description: The notification types
        type: string
      responses:
        200:
          description: OK
      tags:
      - Auto Scaling Notifications
  /?Action=DescribeLaunchConfigurations:
    get:
      summary: Describe Launch Configurations
      description: Describes one or more launch configurations.
      operationId: describeLaunchConfigurations
      x-api-path-slug: actiondescribelaunchconfigurations-get
      parameters:
      - in: query
        name: LaunchConfigurationNames.member.N
        description: The launch configuration names
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of items to return with this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Launch
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