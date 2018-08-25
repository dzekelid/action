---
swagger: "2.0"
x-collection-name: LoginRadius
x-complete: 1
info:
  title: Login Operations
  version: 1.0.0
host: /login
basePath: http://localhost:8008/_matrix/client/api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /login:
    post:
      summary: Submit a login action.
      description: If this is part of a multi-stage login, there MUST be a session
        key.
      operationId: submit_login
      x-api-path-slug: login-post
      parameters:
      - in: body
        name: body
        description: A login submission
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Submit
      - Login
      - Action
---