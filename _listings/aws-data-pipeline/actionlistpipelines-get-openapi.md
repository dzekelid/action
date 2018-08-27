---
swagger: "2.0"
x-collection-name: AWS Data Pipeline
x-complete: 0
info:
  title: AWS Data Pipeline API List Pipelines
  version: 1.0.0
  description: Lists the pipeline identifiers for all active pipelines that you have
    permission to access.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ActivatePipeline:
    get:
      summary: Activate Pipeline
      description: Validates the specified pipeline and starts processing pipeline
        tasks.
      operationId: activatePipeline
      x-api-path-slug: actionactivatepipeline-get
      parameters:
      - in: query
        name: parameterValues
        description: A list of parameter values to pass to the pipeline at activation
        type: string
      - in: query
        name: pipelineId
        description: The ID of the pipeline
        type: string
      - in: query
        name: startTimestamp
        description: The date and time to resume the pipeline
        type: string
      responses:
        200:
          description: OK
      tags:
      - Pipeline
  /?Action=AddTags:
    get:
      summary: Add Tags
      description: Adds or modifies tags for the specified pipeline.
      operationId: addTags
      x-api-path-slug: actionaddtags-get
      parameters:
      - in: query
        name: pipelineId
        description: The ID of the pipeline
        type: string
      - in: query
        name: tags
        description: The tags to add, as key/value pairs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags
  /?Action=CreatePipeline:
    get:
      summary: Create Pipeline
      description: Creates a new, empty pipeline.
      operationId: createPipeline
      x-api-path-slug: actioncreatepipeline-get
      parameters:
      - in: query
        name: description
        description: The description for the pipeline
        type: string
      - in: query
        name: name
        description: The name for the pipeline
        type: string
      - in: query
        name: tags
        description: A list of tags to associate with the pipeline at creation
        type: string
      - in: query
        name: uniqueId
        description: A unique identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Pipeline
  /?Action=DeactivatePipeline:
    get:
      summary: Deactivate Pipeline
      description: Deactivates the specified running pipeline.
      operationId: deactivatePipeline
      x-api-path-slug: actiondeactivatepipeline-get
      parameters:
      - in: query
        name: cancelActive
        description: Indicates whether to cancel any running objects
        type: string
      - in: query
        name: pipelineId
        description: The ID of the pipeline
        type: string
      responses:
        200:
          description: OK
      tags:
      - Pipeline
  /?Action=DeletePipeline:
    get:
      summary: Delete Pipeline
      description: Deletes a pipeline, its pipeline definition, and its run history.
      operationId: deletePipeline
      x-api-path-slug: actiondeletepipeline-get
      parameters:
      - in: query
        name: pipelineId
        description: The ID of the pipeline
        type: string
      responses:
        200:
          description: OK
      tags:
      - Pipeline
  /?Action=DescribeObjects:
    get:
      summary: Describe Objects
      description: Gets the object definitions for a set of objects associated with
        the pipeline.
      operationId: describeObjects
      x-api-path-slug: actiondescribeobjects-get
      parameters:
      - in: query
        name: evaluateExpressions
        description: Indicates whether any expressions in the object should be evaluated
          when the object descriptions are returned
        type: string
      - in: query
        name: marker
        description: The starting point for the results to be returned
        type: string
      - in: query
        name: objectIds
        description: The IDs of the pipeline objects that contain the definitions
          to be described
        type: string
      - in: query
        name: pipelineId
        description: The ID of the pipeline that contains the object definitions
        type: string
      responses:
        200:
          description: OK
      tags:
      - Objects
  /?Action=DescribePipelines:
    get:
      summary: Describe Pipelines
      description: Retrieves metadata about one or more pipelines.
      operationId: describePipelines
      x-api-path-slug: actiondescribepipelines-get
      parameters:
      - in: query
        name: pipelineIds
        description: The IDs of the pipelines to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Pipeline
  /?Action=EvaluateExpression:
    get:
      summary: Evaluate Expression
      description: Task runners call EvaluateExpression to evaluate a string in the
        context of the specified object.
      operationId: evaluateExpression
      x-api-path-slug: actionevaluateexpression-get
      parameters:
      - in: query
        name: expression
        description: The expression to evaluate
        type: string
      - in: query
        name: objectId
        description: The ID of the object
        type: string
      - in: query
        name: pipelineId
        description: The ID of the pipeline
        type: string
      responses:
        200:
          description: OK
      tags:
      - Expressions
  /?Action=GetPipelineDefinition:
    get:
      summary: Get Pipeline Definition
      description: Gets the definition of the specified pipeline.
      operationId: getPipelineDefinition
      x-api-path-slug: actiongetpipelinedefinition-get
      parameters:
      - in: query
        name: pipelineId
        description: The ID of the pipeline
        type: string
      - in: query
        name: version
        description: The version of the pipeline definition to retrieve
        type: string
      responses:
        200:
          description: OK
      tags:
      - Pipeline
  /?Action=ListPipelines:
    get:
      summary: List Pipelines
      description: Lists the pipeline identifiers for all active pipelines that you
        have permission to access.
      operationId: listPipelines
      x-api-path-slug: actionlistpipelines-get
      parameters:
      - in: query
        name: marker
        description: The starting point for the results to be returned
        type: string
      responses:
        200:
          description: OK
      tags:
      - Pipeline
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