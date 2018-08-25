---
swagger: "2.0"
x-collection-name: AWS Data Pipeline
x-complete: 0
info:
  title: AWS Data Pipeline API Create Pipeline
  version: 1.0.0
  description: Creates a new, empty pipeline.
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