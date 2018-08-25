---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Perform a post action
  description: |-
    Perform a post action, which allows users to interact with integrations through posts.
    ##### Permissions
    Must be authenticated and have the `read_channel` permission to the channel the post is in.
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /posts/{post_id}/actions/{action_id}:
    post:
      summary: Perform a post action
      description: |-
        Perform a post action, which allows users to interact with integrations through posts.
        ##### Permissions
        Must be authenticated and have the `read_channel` permission to the channel the post is in.
      operationId: perform-a-post-action-which-allows-users-to-interact-with-integrations-through-posts-permissionsmust
      x-api-path-slug: postspost-idactionsaction-id-post
      parameters:
      - in: path
        name: action_id
        description: Action GUID
      - in: path
        name: post_id
        description: Post GUID
      responses:
        200:
          description: OK
      tags:
      - Perform
      - Post
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