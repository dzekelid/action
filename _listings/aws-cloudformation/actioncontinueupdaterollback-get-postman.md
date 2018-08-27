{
  "info": {
    "name": "AWS CloudFormation API Continue Update Rollback",
    "_postman_id": "e9ce28b9-b3ba-416a-b5d4-5dd1b73ec6a0",
    "description": "For a specified stack that is in the UPDATE_ROLLBACK_FAILED state, continues rolling it back\n         to the UPDATE_ROLLBACK_COMPLETE state.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Stacks",
      "item": [
        {
          "id": "5d990bf8-dcc6-412e-807d-f0cecd5280db",
          "name": "cancelUpdateStack",
          "request": {
            "url": "http://example.com/api/?Action=CancelUpdateStack?StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels an update on the specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ed420bc-6a24-4ac1-a319-ac0109c3868d"
            }
          ]
        }
      ]
    },
    {
      "name": "Rollback",
      "item": [
        {
          "id": "406133e3-f372-42e7-be4d-13f21ea6626f",
          "name": "continueUpdateRollback",
          "request": {
            "url": "http://example.com/api/?Action=ContinueUpdateRollback?ResourcesToSkip.member.N=ResourcesToSkip.member.N&RoleARN=RoleARN&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "For a specified stack that is in the UPDATE_ROLLBACK_FAILED state, continues rolling it back\n         to the UPDATE_ROLLBACK_COMPLETE state."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "26862158-1ba1-458f-804e-b9e506990831"
            }
          ]
        }
      ]
    }
  ]
}