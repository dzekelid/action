swagger: "2.0"
x-collection-name: Mattermost
x-complete: 1
info:
  title: Mattermost
  version: 1.0.0
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