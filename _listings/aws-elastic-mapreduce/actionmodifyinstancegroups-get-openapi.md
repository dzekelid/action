---
swagger: "2.0"
x-collection-name: AWS Elastic MapReduce
x-complete: 0
info:
  title: AWS Elastic MapReduce API Modify Instance Groups
  version: 1.0.0
  description: ModifyInstanceGroups modifies the number of nodes and configuration
    settings of an instance group.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddInstanceGroups:
    get:
      summary: Add Instance Groups
      description: Adds one or more instance groups to a running cluster.
      operationId: addInstanceGroups
      x-api-path-slug: actionaddinstancegroups-get
      parameters:
      - in: query
        name: InstanceGroups
        description: Instance groups to add
        type: string
      - in: query
        name: JobFlowId
        description: Job flow in which to add the instance groups
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance Groups
  /?Action=AddJobFlowSteps:
    get:
      summary: Add Job Flow Steps
      description: AddJobFlowSteps adds new steps to a running job flow.
      operationId: addJobFlowSteps
      x-api-path-slug: actionaddjobflowsteps-get
      parameters:
      - in: query
        name: JobFlowId
        description: A string that uniquely identifies the job flow
        type: string
      - in: query
        name: Steps
        description: A list of StepConfig to be executed by the job flow
        type: string
      responses:
        200:
          description: OK
      tags:
      - Job Flow Steps
  /?Action=AddTags:
    get:
      summary: Add Tags
      description: Adds tags to an Amazon EMR resource.
      operationId: addTags
      x-api-path-slug: actionaddtags-get
      parameters:
      - in: query
        name: ResourceId
        description: The Amazon EMR resource identifier to which tags will be added
        type: string
      - in: query
        name: Tags
        description: A list of tags to associate with a cluster and propagate to EC2
          instances
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags
  /?Action=CancelSteps:
    get:
      summary: Cancel Steps
      description: Cancels a pending step or steps in a running cluster.
      operationId: cancelSteps
      x-api-path-slug: actioncancelsteps-get
      parameters:
      - in: query
        name: ClusterId
        description: The ClusterID for which specified steps will be canceled
        type: string
      - in: query
        name: StepIds
        description: The list of StepIDs to cancel
        type: string
      responses:
        200:
          description: OK
      tags:
      - Steps
  /?Action=CreateSecurityConfiguration:
    get:
      summary: Create Security Configuration
      description: Creates a security configuration, which is stored in the service
        and can be specified when a cluster is created.
      operationId: createSecurityConfiguration
      x-api-path-slug: actioncreatesecurityconfiguration-get
      parameters:
      - in: query
        name: Name
        description: The name of the security configuration
        type: string
      - in: query
        name: SecurityConfiguration
        description: The security configuration details in JSON format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Configurations
  /?Action=DeleteSecurityConfiguration:
    get:
      summary: Delete Security Configuration
      description: Deletes a security configuration.
      operationId: deleteSecurityConfiguration
      x-api-path-slug: actiondeletesecurityconfiguration-get
      parameters:
      - in: query
        name: Name
        description: The name of the security configuration
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Configurations
  /?Action=DescribeCluster:
    get:
      summary: Describe Cluster
      description: Provides cluster-level details including status, hardware and software
        configuration, VPC settings, and so on.
      operationId: describeCluster
      x-api-path-slug: actiondescribecluster-get
      parameters:
      - in: query
        name: ClusterId
        description: The identifier of the cluster to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=DescribeJobFlows:
    get:
      summary: Describe Job Flows
      description: This API is deprecated and will eventually be removed.
      operationId: describeJobFlows
      x-api-path-slug: actiondescribejobflows-get
      parameters:
      - in: query
        name: CreatedAfter
        description: Return only job flows created after this date and time
        type: string
      - in: query
        name: CreatedBefore
        description: Return only job flows created before this date and time
        type: string
      - in: query
        name: JobFlowIds
        description: Return only job flows whose job flow ID is contained in this
          list
        type: string
      - in: query
        name: JobFlowStates
        description: Return only job flows whose state is contained in this list
        type: string
      responses:
        200:
          description: OK
      tags:
      - Job Flows
  /?Action=DescribeSecurityConfiguration:
    get:
      summary: Describe Security Configuration
      description: Provides the details of a security configuration by returning the
        configuration JSON.
      operationId: describeSecurityConfiguration
      x-api-path-slug: actiondescribesecurityconfiguration-get
      parameters:
      - in: query
        name: Name
        description: The name of the security configuration
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Configurations
  /?Action=DescribeStep:
    get:
      summary: Describe Step
      description: Provides more detail about the cluster step.
      operationId: describeStep
      x-api-path-slug: actiondescribestep-get
      parameters:
      - in: query
        name: ClusterId
        description: The identifier of the cluster with steps to describe
        type: string
      - in: query
        name: StepId
        description: The identifier of the step to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Steps
  /?Action=ListBootstrapActions:
    get:
      summary: List Bootstrap Actions
      description: Provides information about the bootstrap actions associated with
        a cluster.
      operationId: listBootstrapActions
      x-api-path-slug: actionlistbootstrapactions-get
      parameters:
      - in: query
        name: ClusterId
        description: The cluster identifier for the bootstrap actions to list
        type: string
      - in: query
        name: Marker
        description: The pagination token that indicates the next set of results to
          retrieve
        type: string
      responses:
        200:
          description: OK
      tags:
      - Bootstrap Actions
  /?Action=ListClusters:
    get:
      summary: List Clusters
      description: Provides the status of all clusters visible to this AWS account.
      operationId: listClusters
      x-api-path-slug: actionlistclusters-get
      parameters:
      - in: query
        name: ClusterStates
        description: The cluster state filters to apply when listing clusters
        type: string
      - in: query
        name: CreatedAfter
        description: The creation date and time beginning value filter for listing
          clusters
        type: string
      - in: query
        name: CreatedBefore
        description: The creation date and time end value filter for listing clusters
        type: string
      - in: query
        name: Marker
        description: The pagination token that indicates the next set of results to
          retrieve
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=ListInstanceGroups:
    get:
      summary: List Instance Groups
      description: Provides all available details about the instance groups in a cluster.
      operationId: listInstanceGroups
      x-api-path-slug: actionlistinstancegroups-get
      parameters:
      - in: query
        name: ClusterId
        description: The identifier of the cluster for which to list the instance
          groups
        type: string
      - in: query
        name: Marker
        description: The pagination token that indicates the next set of results to
          retrieve
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance Groups
  /?Action=ListInstances:
    get:
      summary: List Instances
      description: "Provides information about the cluster instances that Amazon EMR
        provisions on behalf of a user \n         when it creates the cluster."
      operationId: listInstances
      x-api-path-slug: actionlistinstances-get
      parameters:
      - in: query
        name: ClusterId
        description: The identifier of the cluster for which to list the instances
        type: string
      - in: query
        name: InstanceGroupId
        description: The identifier of the instance group for which to list the instances
        type: string
      - in: query
        name: InstanceGroupTypes
        description: The type of instance group for which to list the instances
        type: string
      - in: query
        name: InstanceStates
        description: A list of instance states that will filter the instances returned
          with this request
        type: string
      - in: query
        name: Marker
        description: The pagination token that indicates the next set of results to
          retrieve
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances
  /?Action=ListSecurityConfigurations:
    get:
      summary: List Security Configurations
      description: Lists all the security configurations visible to this account,
        providing their creation dates and times, and their names.
      operationId: listSecurityConfigurations
      x-api-path-slug: actionlistsecurityconfigurations-get
      parameters:
      - in: query
        name: Marker
        description: The pagination token that indicates the set of results to retrieve
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Configurations
  /?Action=ListSteps:
    get:
      summary: List Steps
      description: Provides a list of steps for the cluster in reverse order unless
        you specify stepIds with the request.
      operationId: listSteps
      x-api-path-slug: actionliststeps-get
      parameters:
      - in: query
        name: ClusterId
        description: The identifier of the cluster for which to list the steps
        type: string
      - in: query
        name: Marker
        description: The pagination token that indicates the next set of results to
          retrieve
        type: string
      - in: query
        name: StepIds
        description: The filter to limit the step list based on the identifier of
          the steps
        type: string
      - in: query
        name: StepStates
        description: The filter to limit the step list based on certain states
        type: string
      responses:
        200:
          description: OK
      tags:
      - Steps
  /?Action=ModifyInstanceGroups:
    get:
      summary: Modify Instance Groups
      description: ModifyInstanceGroups modifies the number of nodes and configuration
        settings of an instance group.
      operationId: modifyInstanceGroups
      x-api-path-slug: actionmodifyinstancegroups-get
      parameters:
      - in: query
        name: ClusterId
        description: The ID of the cluster to which the instance group belongs
        type: string
      - in: query
        name: InstanceGroups
        description: Instance groups to change
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance Groups
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