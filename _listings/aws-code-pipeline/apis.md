---
name: AWS Code Pipeline
x-slug: aws-code-pipeline
description: AWS Data Pipeline is a web service that helps you reliably process and
  move data between different AWS compute and storage services, as well as on-premise
  data sources, at specified intervals. With AWS Data Pipeline, you can regularly
  access your data where it&rsquo;s stored, transform and process it at scale, and
  efficiently transfer the results to AWS services such as Amazon S3, Amazon RDS,
  Amazon DynamoDB, and Amazon EMR.AWS Data Pipeline helps you easily create complex
  data processing workloads that are fault tolerant, repeatable, and highly available.
  You don&rsquo;t have to worry about ensuring resource availability, managing inter-task
  dependencies, retrying transient failures or timeouts in individual tasks, or creating
  a failure notification system. AWS Data Pipeline also allows you to move and process
  data that was previously locked up in on-premise data silos.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Action
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Code Pipeline API - Create Custom Action Type
  x-api-slug: actioncreatecustomactiontype-get
  description: |-
    Creates a new custom action that can be used in all pipelines associated with the
                AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actioncreatecustomactiontype-get-openapi.md
- name: AWS Code Pipeline API - Delete Custom Action Type
  x-api-slug: actiondeletecustomactiontype-get
  description: Marks a custom action as deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actiondeletecustomactiontype-get-openapi.md
- name: AWS Code Pipeline API - List Action Types
  x-api-slug: actionlistactiontypes-get
  description: |-
    Gets a summary of all AWS CodePipeline action types associated with your
                account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionlistactiontypes-get-openapi.md
- name: AWS Code Pipeline API - Put Action Revision
  x-api-slug: actionputactionrevision-get
  description: Provides information to AWS CodePipeline about new revisions to a source.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionputactionrevision-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionputactionrevision-get-openapi.md
- name: AWS Code Pipeline API - Acknowledge Job
  x-api-slug: actionacknowledgejob-get
  description: |-
    Returns information about a specified job and whether that job has been received by
                the job worker.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionacknowledgejob-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionacknowledgejob-get-openapi.md
- name: AWS Code Pipeline API - Acknowledge Third Party Job
  x-api-slug: actionacknowledgethirdpartyjob-get
  description: Confirms a job worker has received the specified job.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionacknowledgethirdpartyjob-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionacknowledgethirdpartyjob-get-openapi.md
- name: AWS Code Pipeline API - Create Pipeline
  x-api-slug: actioncreatepipeline-get
  description: Creates a pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actioncreatepipeline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actioncreatepipeline-get-openapi.md
- name: AWS Code Pipeline API - Delete Pipeline
  x-api-slug: actiondeletepipeline-get
  description: Deletes the specified pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actiondeletepipeline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actiondeletepipeline-get-openapi.md
- name: AWS Code Pipeline API - Disable Stage Transition
  x-api-slug: actiondisablestagetransition-get
  description: |-
    Prevents artifacts in a pipeline from transitioning to the next stage in the
                pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actiondisablestagetransition-get-openapi.md
- name: AWS Code Pipeline API - Enable Stage Transition
  x-api-slug: actionenablestagetransition-get
  description: Enables artifacts in a pipeline to transition to a stage in a pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionenablestagetransition-get-openapi.md
- name: AWS Code Pipeline API - Get Job Details
  x-api-slug: actiongetjobdetails-get
  description: Returns information about a job.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actiongetjobdetails-get-openapi.md
- name: AWS Code Pipeline API - Get Pipeline
  x-api-slug: actiongetpipeline-get
  description: Returns the metadata, structure, stages, and actions of a pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actiongetpipeline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actiongetpipeline-get-openapi.md
- name: AWS Code Pipeline API - Get Pipeline Execution
  x-api-slug: actiongetpipelineexecution-get
  description: |-
    Returns information about an execution of a pipeline, including details about
                artifacts, the pipeline execution ID, and the name, version, and status of the
                pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actiongetpipelineexecution-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actiongetpipelineexecution-get-openapi.md
- name: AWS Code Pipeline API - Get Pipeline State
  x-api-slug: actiongetpipelinestate-get
  description: |-
    Returns information about the state of a pipeline, including the stages and
                actions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actiongetpipelinestate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actiongetpipelinestate-get-openapi.md
- name: AWS Code Pipeline API - Get Third Party Job Details
  x-api-slug: actiongetthirdpartyjobdetails-get
  description: Requests the details of a job for a third party action.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actiongetthirdpartyjobdetails-get-openapi.md
- name: AWS Code Pipeline API - List Pipelines
  x-api-slug: actionlistpipelines-get
  description: Gets a summary of all of the pipelines associated with your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionlistpipelines-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionlistpipelines-get-openapi.md
- name: AWS Code Pipeline API - Poll For Jobs
  x-api-slug: actionpollforjobs-get
  description: Returns information about any jobs for AWS CodePipeline to act upon.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionpollforjobs-get-openapi.md
- name: AWS Code Pipeline API - Poll For Third Party Jobs
  x-api-slug: actionpollforthirdpartyjobs-get
  description: Determines whether there are any third party jobs for a job worker
    to act on.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionpollforthirdpartyjobs-get-openapi.md
- name: AWS Code Pipeline API - Put Approval Result
  x-api-slug: actionputapprovalresult-get
  description: Provides the response to a manual approval request to AWS CodePipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionputapprovalresult-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionputapprovalresult-get-openapi.md
- name: AWS Code Pipeline API - Put Job Failure Result
  x-api-slug: actionputjobfailureresult-get
  description: Represents the failure of a job as returned to the pipeline by a job
    worker.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionputjobfailureresult-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionputjobfailureresult-get-openapi.md
- name: AWS Code Pipeline API - Put Job Success Result
  x-api-slug: actionputjobsuccessresult-get
  description: Represents the success of a job as returned to the pipeline by a job
    worker.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionputjobsuccessresult-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionputjobsuccessresult-get-openapi.md
- name: AWS Code Pipeline API - Put Third Party Job Failure Result
  x-api-slug: actionputthirdpartyjobfailureresult-get
  description: |-
    Represents the failure of a third party job as returned to the pipeline by a job
                worker.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionputthirdpartyjobfailureresult-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionputthirdpartyjobfailureresult-get-openapi.md
- name: AWS Code Pipeline API - Put Third Party Job Success Result
  x-api-slug: actionputthirdpartyjobsuccessresult-get
  description: |-
    Represents the success of a third party job as returned to the pipeline by a job
                worker.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionputthirdpartyjobsuccessresult-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionputthirdpartyjobsuccessresult-get-openapi.md
- name: AWS Code Pipeline API - Retry Stage Execution
  x-api-slug: actionretrystageexecution-get
  description: |-
    Resumes the pipeline execution by retrying the last failed actions in a
                stage.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionretrystageexecution-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionretrystageexecution-get-openapi.md
- name: AWS Code Pipeline API - Start Pipeline Execution
  x-api-slug: actionstartpipelineexecution-get
  description: Starts the specified pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionstartpipelineexecution-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionstartpipelineexecution-get-openapi.md
- name: AWS Code Pipeline API - Update Pipeline
  x-api-slug: actionupdatepipeline-get
  description: Updates a specified pipeline with edits or changes to its structure.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodePipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: Amazon Web Services, SDK, Data, Orchestration, Stack Network, API Service
    Provider, API Service Provider, API Provider, Migrations, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionupdatepipeline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-code-pipeline/actionupdatepipeline-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.cloudwatch.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.code.pipeline.stack.network
- type: x-blog
  url: http://blogs.aws.amazon.com/bigdata
- type: x-change-log
  url: http://aws.amazon.com/releasenotes/AWS-Data-Pipeline/
- type: x-documentation
  url: http://docs.aws.amazon.com/datapipeline/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/datapipeline/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=151
- type: x-pricing
  url: https://aws.amazon.com/datapipeline/pricing/
- type: x-tools
  url: http://aws.amazon.com/developertools/AWS-Data-Pipeline/
- type: x-website
  url: https://aws.amazon.com/datapipeline/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---