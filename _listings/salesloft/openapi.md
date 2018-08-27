swagger: "2.0"
x-collection-name: SalesLoft
x-complete: 1
info:
  title: SalesLoft
  description: salesloft-helps-transform-sales-teams-into-modern-sales-organizations---converting-more-target-accounts-into-customer-accounts
  version: v2
host: api.salesloft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/actions/{id}.json:
    get:
      summary: Fetch an action
      description: |-
        Fetches an action, by ID only.
        This endpoint will only return actions that are in_progress or pending_activity.
        Once an action is complete, the request for that action will return a 404 status code.
      operationId: v2.actions.id.json.get
      x-api-path-slug: v2actionsid-json-get
      parameters:
      - in: path
        name: id
        description: Action ID
      responses:
        200:
          description: OK
      tags:
      - Sales
      - Fetch
      - Action