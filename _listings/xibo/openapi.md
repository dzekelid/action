---
swagger: "2.0"
x-collection-name: Xibo
x-complete: 1
info:
  title: Xibo API
  description: xibo-cms-api
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
  /displaygroup/{displayGroupId}/action/clearStatsAndLogs:
    post:
      summary: 'Action: Clear Stats and Logs'
      description: Clear all stats and logs on this Group
      operationId: displayGroupActionClearStatsAndLogs
      x-api-path-slug: displaygroupdisplaygroupidactionclearstatsandlogs-post
      parameters:
      - in: path
        name: displayGroupId
        description: The display group id
      responses:
        200:
          description: OK
      tags:
      - 'Action:'
      - Clear
      - Stats
      - Logs
  /displaygroup/{displayGroupId}/action/changeLayout:
    post:
      summary: 'Action: Change Layout'
      description: Send the change layout action to this DisplayGroup
      operationId: displayGroupActionChangeLayout
      x-api-path-slug: displaygroupdisplaygroupidactionchangelayout-post
      parameters:
      - in: formData
        name: changeMode
        description: Whether to queue or replace with this action
      - in: path
        name: displayGroupId
        description: The Display Group Id
      - in: formData
        name: downloadRequired
        description: Flag indicating whether the player should perform a collect before
          playing the Layout
      - in: formData
        name: duration
        description: The duration in seconds for this Layout change to remain in effect
      - in: formData
        name: layoutId
        description: The Layout Id
      responses:
        200:
          description: OK
      tags:
      - 'Action:'
      - Change
      - Layout
  /displaygroup/{displayGroupId}/action/revertToSchedule:
    post:
      summary: 'Action: Revert to Schedule'
      description: Send the revert to schedule action to this DisplayGroup
      operationId: displayGroupActionRevertToSchedule
      x-api-path-slug: displaygroupdisplaygroupidactionreverttoschedule-post
      parameters:
      - in: path
        name: displayGroupId
        description: The display group id
      responses:
        200:
          description: OK
      tags:
      - 'Action:'
      - Revert
      - To
      - Schedule
  /displaygroup/{displayGroupId}/action/overlayLayout:
    post:
      summary: 'Action: Overlay Layout'
      description: Send the overlay layout action to this DisplayGroup
      operationId: displayGroupActionOverlayLayout
      x-api-path-slug: displaygroupdisplaygroupidactionoverlaylayout-post
      parameters:
      - in: path
        name: displayGroupId
        description: The Display Group Id
      - in: formData
        name: downloadRequired
        description: Flag indicating whether the player should perform a collect before
          adding the Overlay
      - in: formData
        name: duration
        description: The duration in seconds for this Overlay to remain in effect
      - in: formData
        name: layoutId
        description: The Layout Id
      responses:
        200:
          description: OK
      tags:
      - 'Action:'
      - Overlay
      - Layout
---