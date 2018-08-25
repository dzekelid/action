---
swagger: "2.0"
x-collection-name: AWS CloudSearch
x-complete: 0
info:
  title: AWS CloudSearch Describe Domains
  version: 1.0.0
  description: Gets information about the search domains owned by this account.
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
  /?Action=DefineAnalysisScheme:
    get:
      summary: Define Analysis Scheme
      description: Configures an analysis scheme that can be applied to a text or
        text-array field to define language-specific text processing options.
      operationId: DefineAnalysisScheme
      x-api-path-slug: actiondefineanalysisscheme-get
      parameters:
      - in: query
        name: AnalysisScheme
        description: Configuration information for an analysis scheme
        type: string
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Analysis Scheme
  /?Action=DefineExpression:
    get:
      summary: Define Expression
      description: Configures an Expression  for the search domain.
      operationId: DefineExpression
      x-api-path-slug: actiondefineexpression-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      - in: query
        name: Expression
        description: A named expression that can be evaluated at search time
        type: string
      responses:
        200:
          description: OK
      tags:
      - Expressions
  /?Action=DefineIndexField:
    get:
      summary: Define Index Field
      description: Configures an ndexField  for the search domain.
      operationId: DefineIndexField
      x-api-path-slug: actiondefineindexfield-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      - in: query
        name: IndexField
        description: The index field and field options you want to configure
        type: string
      responses:
        200:
          description: OK
      tags:
      - Index Fields
  /?Action=DefineSuggester:
    get:
      summary: Define Suggester
      description: Configures a suggester for a domain.
      operationId: DefineSuggester
      x-api-path-slug: actiondefinesuggester-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      - in: query
        name: Suggester
        description: Configuration information for a search suggester
        type: string
      responses:
        200:
          description: OK
      tags:
      - Suggesters
  /?Action=DeleteAnalysisScheme:
    get:
      summary: Delete Analysis Scheme
      description: Deletes an analysis scheme.
      operationId: DeleteAnalysisScheme
      x-api-path-slug: actiondeleteanalysisscheme-get
      parameters:
      - in: query
        name: AnalysisSchemeName
        description: The name of the analysis scheme you want to delete
        type: string
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Analysis Scheme
  /?Action=DeleteDomain:
    get:
      summary: Delete Domain
      description: Permanently deletes a search domain and all of its data.
      operationId: DeleteDomain
      x-api-path-slug: actiondeletedomain-get
      parameters:
      - in: query
        name: DomainName
        description: The name of the domain you want to permanently delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Domains
  /?Action=DeleteExpression:
    get:
      summary: Delete Expression
      description: "Removes an \n  Expression\n  from the search domain."
      operationId: DeleteExpression
      x-api-path-slug: actiondeleteexpression-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      - in: query
        name: ExpressionName
        description: The name of the                         Expression                      to
          delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Expressions
  /?Action=DeleteIndexField:
    get:
      summary: Delete Index Field
      description: "Removes an \n  IndexField\n  from the search domain."
      operationId: DeleteIndexField
      x-api-path-slug: actiondeleteindexfield-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      - in: query
        name: IndexFieldName
        description: The name of the index field your want to remove from the domains
          indexing options
        type: string
      responses:
        200:
          description: OK
      tags:
      - Index Fields
  /?Action=DeleteSuggester:
    get:
      summary: Delete Suggester
      description: Deletes a suggester.
      operationId: DeleteSuggester
      x-api-path-slug: actiondeletesuggester-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      - in: query
        name: SuggesterName
        description: Specifies the name of the suggester you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Suggesters
  /?Action=DescribeAnalysisSchemes:
    get:
      summary: Describe Analysis Schemes
      description: Gets the analysis schemes configured for a domain.
      operationId: DescribeAnalysisSchemes
      x-api-path-slug: actiondescribeanalysisschemes-get
      parameters:
      - in: query
        name: AnalysisSchemeNames.member.N
        description: The analysis schemes you want to describe
        type: string
      - in: query
        name: Deployed
        description: Whether to display the deployed configuration (true) or include
          any pending changes (false)
        type: string
      - in: query
        name: DomainName
        description: The name of the domain you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Analysis Scheme
  /?Action=DescribeAvailabilityOptions:
    get:
      summary: Describe Availability Options
      description: Gets the availability options configured for a domain.
      operationId: DescribeAvailabilityOptions
      x-api-path-slug: actiondescribeavailabilityoptions-get
      parameters:
      - in: query
        name: Deployed
        description: Whether to display the deployed configuration (true) or include
          any pending changes (false)
        type: string
      - in: query
        name: DomainName
        description: The name of the domain you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Availability Options
  /?Action=DescribeDomains:
    get:
      summary: Describe Domains
      description: Gets information about the search domains owned by this account.
      operationId: DescribeDomains
      x-api-path-slug: actiondescribedomains-get
      parameters:
      - in: query
        name: DomainNames.member.N
        description: The names of the domains you want to include in the response
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