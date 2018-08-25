---
swagger: "2.0"
x-collection-name: AWS Config
x-complete: 0
info:
  title: AWS Config API Describe Compliance By Config Rule
  version: 1.0.0
  description: Indicates whether the specified AWS Config rules are compliant.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteConfigRule:
    get:
      summary: Delete Config Rule
      description: Deletes the specified AWS Config rule and all of its evaluation
        results.
      operationId: deleteConfigRule
      x-api-path-slug: actiondeleteconfigrule-get
      parameters:
      - in: query
        name: ConfigRuleName
        description: The name of the AWS Config rule that you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Rules
  /?Action=DeleteConfigurationRecorder:
    get:
      summary: Delete Configuration Recorder
      description: Deletes the configuration recorder.
      operationId: deleteConfigurationRecorder
      x-api-path-slug: actiondeleteconfigurationrecorder-get
      parameters:
      - in: query
        name: ConfigurationRecorderName
        description: The name of the configuration recorder to be deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Recorders
  /?Action=DeleteDeliveryChannel:
    get:
      summary: Delete Delivery Channel
      description: Deletes the delivery channel.
      operationId: deleteDeliveryChannel
      x-api-path-slug: actiondeletedeliverychannel-get
      parameters:
      - in: query
        name: DeliveryChannelName
        description: The name of the delivery channel to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Delivery Channels
  /?Action=DeleteEvaluationResults:
    get:
      summary: Delete Evaluation Results
      description: Deletes the evaluation results for the specified Config rule.
      operationId: deleteEvaluationResults
      x-api-path-slug: actiondeleteevaluationresults-get
      parameters:
      - in: query
        name: ConfigRuleName
        description: The name of the Config rule for which you want to delete the
          evaluation results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Evaluations
  /?Action=DeliverConfigSnapshot:
    get:
      summary: Deliver Config Snapshot
      description: Schedules delivery of a configuration snapshot to the Amazon S3
        bucket in the specified delivery channel.
      operationId: deliverConfigSnapshot
      x-api-path-slug: actiondeliverconfigsnapshot-get
      parameters:
      - in: query
        name: deliveryChannelName
        description: The name of the delivery channel through which the snapshot is
          delivered
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Snapshot
  /?Action=DescribeComplianceByConfigRule:
    get:
      summary: Describe Compliance By Config Rule
      description: Indicates whether the specified AWS Config rules are compliant.
      operationId: describeComplianceByConfigRule
      x-api-path-slug: actiondescribecompliancebyconfigrule-get
      parameters:
      - in: query
        name: ComplianceTypes
        description: Filters the results by compliance
        type: string
      - in: query
        name: ConfigRuleNames
        description: Specify one or more AWS Config rule names to filter the results
          by rule
        type: string
      - in: query
        name: NextToken
        description: The nextToken string returned on a previous page thatyou use
          to get the next page of results in a paginated response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Compliance
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