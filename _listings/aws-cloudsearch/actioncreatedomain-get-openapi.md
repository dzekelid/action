---
swagger: "2.0"
x-collection-name: AWS CloudSearch
x-complete: 0
info:
  title: AWS CloudSearch Create Domain
  version: 1.0.0
  description: Creates a new search domain.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddTags:
    get:
      summary: Add Tags
      description: |-
        Attaches resource tags to an
         Amazon CloudSearch domain.
      operationId: AddTags
      x-api-path-slug: actionaddtags-get
      parameters:
      - in: query
        name: Base
        description: An                  error occurred while processing the request
        type: string
      - in: query
        name: InternalException
        description: The processing of the request failed because of an internal service
          error
        type: string
      - in: query
        name: LimitExceededException
        description: The request contains more than the allowed number and type of
          Amazon CloudSearch domain                  resources
        type: string
      - in: query
        name: ValidationException
        description: The request contains invalid input or is missing required input
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags
  /?Action=BuildSuggesters:
    get:
      summary: Build Suggesters
      description: Indexes the search suggestions.
      operationId: BuildSuggesters
      x-api-path-slug: actionbuildsuggesters-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Suggesters
  /?Action=CreateDomain:
    get:
      summary: Create Domain
      description: Creates a new search domain.
      operationId: CreateDomain
      x-api-path-slug: actioncreatedomain-get
      parameters:
      - in: query
        name: DomainName
        description: A name for the domain you are creating
        type: string
      responses:
        200:
          description: OK
      tags:
      - Domains
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