---
swagger: "2.0"
x-collection-name: Xibo
x-complete: 0
info:
  title: 'Xibo API Action: Collect Now'
  description: Send the collect now action to this DisplayGroup
  termsOfService: http://xibo.org.uk/legal
  version: 1.0.0
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /displaygroup/{displayGroupId}/action/collectNow:
    post:
      summary: 'Action: Collect Now'
      description: Send the collect now action to this DisplayGroup
      operationId: displayGroupActionCollectNow
      x-api-path-slug: displaygroupdisplaygroupidactioncollectnow-post
      parameters:
      - in: path
        name: displayGroupId
        description: The display group id
      responses:
        200:
          description: OK
      tags:
      - 'Action:'
      - Collect
      - Now
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