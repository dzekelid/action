swagger: "2.0"
x-collection-name: Twine
x-complete: 1
info:
  title: Twine
  description: -overviewthe-twine-health-api-is-restful-api--the-requests-and-responses-are-formated-according-to-the-json-apihttpjsonapi-orgformat1-0-specification-in-addition-to-this-documentation-we-also-provide-an-openapihttpsgithub-comoaiopenapispecificationblobmasterversions2-0-md-yaml-file-describing-the-api-twine-api-specificationswagger-yaml--authenticationauthentication-for-the-twine-api-is-based-on-the-oauth-2-0-authorization-frameworkhttpstools-ietf-orghtmlrfc6749--twine-currently-supports-grant-types-of-client-credentials-and-refresh-token-see-post-oauthtokenoperationcreatetoken-for-details-on-the-request-and-response-formats--redocinject-securitydefinitions-
  version: 7.18.0
host: api.twinehealth.com
basePath: /pub
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /action:
    post:
      summary: Create action
      description: Create a plan action
      operationId: createAction
      x-api-path-slug: action-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Wearables
      - Action
  /action/{id}:
    get:
      summary: Get an action
      description: Get a health action from a patient's plan.
      operationId: fetchAction
      x-api-path-slug: actionid-get
      parameters:
      - in: path
        name: id
        description: Action identifier
      responses:
        200:
          description: OK
      tags:
      - Wearables
      - Action
    patch:
      summary: Update an action
      description: Update a health action from a patient's plan.
      operationId: updateAction
      x-api-path-slug: actionid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Action identifier
      responses:
        200:
          description: OK
      tags:
      - Wearables
      - Action