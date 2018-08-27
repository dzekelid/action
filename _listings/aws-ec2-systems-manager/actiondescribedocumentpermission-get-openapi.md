---
swagger: "2.0"
x-collection-name: AWS EC2 Systems Manager
x-complete: 0
info:
  title: Amazon EC2 Systems Manager API Describe Document Permission
  version: 1.0.0
  description: Describes the permissions for an SSM document.
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
      description: Adds or overwrites one or more tags for the specified resource.
      operationId: addTagsToResource
      x-api-path-slug: actionaddtagstoresource-get
      parameters:
      - in: query
        name: ResourceId
        description: The resource ID you want to tag
        type: string
      - in: query
        name: ResourceType
        description: Specifies the type of resource you are tagging
        type: string
      - in: query
        name: Tags
        description: One or more tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - Resources
  /?Action=CancelCommand:
    get:
      summary: Cancel Command
      description: Attempts to cancel the command specified by the Command ID.
      operationId: cancelCommand
      x-api-path-slug: actioncancelcommand-get
      parameters:
      - in: query
        name: CommandId
        description: The ID of the command you want to cancel
        type: string
      - in: query
        name: InstanceIds
        description: (Optional) A list of instance IDs on which you want to cancel
          the command
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cancel
      - Command
  /?Action=CreateActivation:
    get:
      summary: Create Activation
      description: |-
        Registers your on-premises server or virtual machine with Amazon EC2 so that you can manage
           these resources using Run Command.
      operationId: createActivation
      x-api-path-slug: actioncreateactivation-get
      parameters:
      - in: query
        name: DefaultInstanceName
        description: The name of the registered, managed instance as it will appear
          in the Amazon EC2 console or   when you use the AWS command line tools to
          list EC2 resources
        type: string
      - in: query
        name: Description
        description: A user-defined description of the resource that you want to register
          with Amazon EC2
        type: string
      - in: query
        name: ExpirationDate
        description: The date by which this activation request should expire
        type: string
      - in: query
        name: IamRole
        description: The Amazon Identity and Access Management (IAM) role that you
          want to assign to the   managed instance
        type: string
      - in: query
        name: RegistrationLimit
        description: Specify the maximum number of managed instances you want to register
        type: string
      responses:
        200:
          description: OK
      tags:
      - Activation
  /?Action=CreateAssociation:
    get:
      summary: Create Association
      description: Associates the specified SSM document with the specified instances
        or targets.
      operationId: createAssociation
      x-api-path-slug: actioncreateassociation-get
      parameters:
      - in: query
        name: DocumentVersion
        description: The document version you want to associate with the target(s)
        type: string
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      - in: query
        name: Name
        description: The name of the SSM document
        type: string
      - in: query
        name: OutputLocation
        description: An Amazon S3 bucket where you want to store the output details
          of the request
        type: string
      - in: query
        name: Parameters
        description: The parameters for the documents runtime configuration
        type: string
      - in: query
        name: ScheduleExpression
        description: A cron expression when the association will be applied to the
          target(s)
        type: string
      - in: query
        name: Targets
        description: The targets (either instances or tags) for the association
        type: string
      responses:
        200:
          description: OK
      tags:
      - Association
  /?Action=CreateAssociationBatch:
    get:
      summary: Create Association Batch
      description: Associates the specified SSM document with the specified instances
        or targets.
      operationId: createAssociationBatch
      x-api-path-slug: actioncreateassociationbatch-get
      parameters:
      - in: query
        name: Entries
        description: One or more associations
        type: string
      responses:
        200:
          description: OK
      tags:
      - Association
      - Batch
  /?Action=CreateDocument:
    get:
      summary: Create Document
      description: Creates an SSM document.
      operationId: createDocument
      x-api-path-slug: actioncreatedocument-get
      parameters:
      - in: query
        name: Content
        description: A valid JSON string
        type: string
      - in: query
        name: DocumentType
        description: The type of document to create
        type: string
      - in: query
        name: Name
        description: A name for the SSM document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Document
  /?Action=CreateMaintenanceWindow:
    get:
      summary: Create Maintenance Window
      description: Creates a new Maintenance Window.
      operationId: createMaintenanceWindow
      x-api-path-slug: actioncreatemaintenancewindow-get
      parameters:
      - in: query
        name: AllowUnassociatedTargets
        description: Whether targets must be registered with the Maintenance Window
          before tasks can be   defined for those targets
        type: string
      - in: query
        name: ClientToken
        description: User-provided idempotency token
        type: string
      - in: query
        name: Cutoff
        description: The number of hours before the end of the Maintenance Window
          that Systems Manager stops   scheduling new tasks for execution
        type: string
      - in: query
        name: Duration
        description: The duration of the Maintenance Window in hours
        type: string
      - in: query
        name: Name
        description: The name of the Maintenance Window
        type: string
      - in: query
        name: Schedule
        description: The schedule of the Maintenance Window in the form of a cron
          or rate   expression
        type: string
      responses:
        200:
          description: OK
      tags:
      - Maintenance
      - Window
  /?Action=CreatePatchBaseline:
    get:
      summary: Create Patch Baseline
      description: Creates a patch baseline.
      operationId: createPatchBaseline
      x-api-path-slug: actioncreatepatchbaseline-get
      parameters:
      - in: query
        name: ApprovalRules
        description: A set of rules used to include patches in the baseline
        type: string
      - in: query
        name: ApprovedPatches
        description: A list of explicitly approved patches for the baseline
        type: string
      - in: query
        name: ClientToken
        description: Caller-provided idempotency token
        type: string
      - in: query
        name: Description
        description: A description of the patch baseline
        type: string
      - in: query
        name: GlobalFilters
        description: A set of global filters used to exclude patches from the baseline
        type: string
      - in: query
        name: Name
        description: The name of the patch baseline
        type: string
      - in: query
        name: RejectedPatches
        description: A list of explicitly rejected patches for the baseline
        type: string
      responses:
        200:
          description: OK
      tags:
      - Baseline
  /?Action=DeleteActivation:
    get:
      summary: Delete Activation
      description: Deletes an activation.
      operationId: deleteActivation
      x-api-path-slug: actiondeleteactivation-get
      parameters:
      - in: query
        name: ActivationId
        description: The ID of the activation that you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Activation
  /?Action=DeleteAssociation:
    get:
      summary: Delete Association
      description: Disassociates the specified SSM document from the specified instance.
      operationId: deleteAssociation
      x-api-path-slug: actiondeleteassociation-get
      parameters:
      - in: query
        name: AssociationId
        description: The association ID that you want to delete
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: Name
        description: The name of the SSM document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Association
  /?Action=DeleteDocument:
    get:
      summary: Delete Document
      description: Deletes the SSM document and all instance associations to the document.
      operationId: deleteDocument
      x-api-path-slug: actiondeletedocument-get
      parameters:
      - in: query
        name: Name
        description: The name of the SSM document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Document
  /?Action=DeleteMaintenanceWindow:
    get:
      summary: Delete Maintenance Window
      description: Deletes a Maintenance Window.
      operationId: deleteMaintenanceWindow
      x-api-path-slug: actiondeletemaintenancewindow-get
      parameters:
      - in: query
        name: WindowId
        description: The ID of the Maintenance Window to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Maintenance
      - Window
  /?Action=DeleteParameter:
    get:
      summary: Delete Parameter
      description: Delete a parameter from the system.
      operationId: deleteParameter
      x-api-path-slug: actiondeleteparameter-get
      parameters:
      - in: query
        name: Name
        description: The name of the parameter to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameter
  /?Action=DeletePatchBaseline:
    get:
      summary: Delete Patch Baseline
      description: Deletes a patch baseline.
      operationId: deletePatchBaseline
      x-api-path-slug: actiondeletepatchbaseline-get
      parameters:
      - in: query
        name: BaselineId
        description: The ID of the patch baseline to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Baseline
  /?Action=DeregisterManagedInstance:
    get:
      summary: Deregister Managed Instance
      description: Removes the server or virtual machine from the list of registered
        servers.
      operationId: deregisterManagedInstance
      x-api-path-slug: actionderegistermanagedinstance-get
      parameters:
      - in: query
        name: InstanceId
        description: The ID assigned to the managed instance when you registered it
          using the activation   process
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deregister
      - Managed
      - Instance
  /?Action=DeregisterPatchBaselineForPatchGroup:
    get:
      summary: Deregister Patch Baseline For Patch Group
      description: Removes a patch group from a patch baseline.
      operationId: deregisterPatchBaselineForPatchGroup
      x-api-path-slug: actionderegisterpatchbaselineforpatchgroup-get
      parameters:
      - in: query
        name: BaselineId
        description: The ID of the patch baseline to deregister the patch group from
        type: string
      - in: query
        name: PatchGroup
        description: The name of the patch group that should be deregistered from
          the patch baseline
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deregister
      - BaselineGroup
  /?Action=DeregisterTargetFromMaintenanceWindow:
    get:
      summary: Deregister Target From Maintenance Window
      description: Removes a target from a Maintenance Window.
      operationId: deregisterTargetFromMaintenanceWindow
      x-api-path-slug: actionderegistertargetfrommaintenancewindow-get
      parameters:
      - in: query
        name: WindowId
        description: The ID of the Maintenance Window the target should be removed
          from
        type: string
      - in: query
        name: WindowTargetId
        description: The ID of the target definition to remove
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deregister
      - Target
      - From
      - Maintenance
      - Window
  /?Action=DeregisterTaskFromMaintenanceWindow:
    get:
      summary: Deregister Task From Maintenance Window
      description: Removes a task from a Maintenance Window.
      operationId: deregisterTaskFromMaintenanceWindow
      x-api-path-slug: actionderegistertaskfrommaintenancewindow-get
      parameters:
      - in: query
        name: WindowId
        description: The ID of the Maintenance Window the task should be removed from
        type: string
      - in: query
        name: WindowTaskId
        description: The ID of the task to remove from the Maintenance Window
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deregister
      - Task
      - From
      - Maintenance
      - Window
  /?Action=DescribeActivations:
    get:
      summary: Describe Activations
      description: |-
        Details about the activation, including: the date and time the activation was created,
           the expiration date, the IAM role assigned to the instances in the activation, and the number of
           instances activated by this registration.
      operationId: describeActivations
      x-api-path-slug: actiondescribeactivations-get
      parameters:
      - in: query
        name: Filters
        description: A filter to view information about your activations
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: A token to start the list
        type: string
      responses:
        200:
          description: OK
      tags:
      - Activations
  /?Action=DescribeAssociation:
    get:
      summary: Describe Association
      description: Describes the associations for the specified SSM document or instance.
      operationId: describeAssociation
      x-api-path-slug: actiondescribeassociation-get
      parameters:
      - in: query
        name: AssociationId
        description: The association ID for which you want information
        type: string
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      - in: query
        name: Name
        description: The name of the SSM document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Association
  /?Action=DescribeAutomationExecutions:
    get:
      summary: Describe Automation Executions
      description: Provides details about all active and terminated Automation executions.
      operationId: describeAutomationExecutions
      x-api-path-slug: actiondescribeautomationexecutions-get
      parameters:
      - in: query
        name: Filters
        description: Filters used to limit the scope of executions that are requested
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Automation
      - Executions
  /?Action=DescribeAvailablePatches:
    get:
      summary: Describe Available Patches
      description: Lists all patches that could possibly be included in a patch baseline.
      operationId: describeAvailablePatches
      x-api-path-slug: actiondescribeavailablepatches-get
      parameters:
      - in: query
        name: Filters
        description: Filters used to scope down the returned patches
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of patches to return (per page)
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Available
      - Patches
  /?Action=DescribeDocument:
    get:
      summary: Describe Document
      description: Describes the specified SSM document.
      operationId: describeDocument
      x-api-path-slug: actiondescribedocument-get
      parameters:
      - in: query
        name: DocumentVersion
        description: The document version for which you want information
        type: string
      - in: query
        name: Name
        description: The name of the SSM document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Document
  /?Action=DescribeDocumentPermission:
    get:
      summary: Describe Document Permission
      description: Describes the permissions for an SSM document.
      operationId: describeDocumentPermission
      x-api-path-slug: actiondescribedocumentpermission-get
      parameters:
      - in: query
        name: Name
        description: The name of the document for which you are the owner
        type: string
      - in: query
        name: PermissionType
        description: The permission type for the document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Document
      - Permission
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