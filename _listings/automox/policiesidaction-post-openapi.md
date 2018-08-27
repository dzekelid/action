---
swagger: "2.0"
x-collection-name: Automox
x-complete: 0
info:
  title: Automox Post Policies Action
  description: Schedule a policy for immediate remediation
  termsOfService: https://www.automox.com/
  contact:
    name: support@automox.com
  version: 1.0.0
host: console.automox.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /policies/{id}/action:
    post:
      summary: Post Policies Action
      description: Schedule a policy for immediate remediation
      operationId: schedule-a-policy-for-immediate-remediation
      x-api-path-slug: policiesidaction-post
      parameters:
      - in: formData
        name: action
        description: Remediation action type [remediateAll]
      - in: path
        name: id
        description: Policy ID
      - in: query
        name: o
        description: Organization ID
      responses:
        200:
          description: OK
      tags:
      - Policies
      - Action
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