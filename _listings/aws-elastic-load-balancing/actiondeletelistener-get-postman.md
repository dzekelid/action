{
  "info": {
    "name": "AWS Elastic Load Balancing API Delete Listener",
    "_postman_id": "732e526b-5268-4896-b1f7-72a4f182bbcd",
    "description": "Deletes the specified listener.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tags",
      "item": [
        {
          "id": "f7b6d7d8-6039-435c-b301-4097d58b413c",
          "name": "addTags",
          "request": {
            "url": "http://example.com/api/?Action=AddTags?ResourceArns.member.N=ResourceArns.member.N&Tags.member.N=Tags.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the specified tags to the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0dfb63f0-9c1a-4170-9220-9a3b86daf0cb"
            }
          ]
        }
      ]
    },
    {
      "name": "Listeners",
      "item": [
        {
          "id": "ad8eb97e-a7a4-4f1a-944a-e1956040db8e",
          "name": "createListener",
          "request": {
            "url": "http://example.com/api/?Action=CreateListener?Certificates.member.N=Certificates.member.N&DefaultActions.member.N=DefaultActions.member.N&LoadBalancerArn=LoadBalancerArn&Port=Port&Protocol=Protocol&SslPolicy=SslPolicy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a listener for the specified Application Load Balancer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0e832f4-59fe-44a6-bcef-6895529b1e2b"
            }
          ]
        },
        {
          "id": "1b2e303e-2915-4842-bd98-d765e2b7b5d4",
          "name": "deleteListener",
          "request": {
            "url": "http://example.com/api/?Action=DeleteListener?ListenerArn=ListenerArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified listener."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2825ed78-16da-42f8-86c5-7e0113bd71cb"
            }
          ]
        }
      ]
    },
    {
      "name": "Load Balancers",
      "item": [
        {
          "id": "c9741031-a25a-49dd-ac6b-85f793afd39d",
          "name": "createLoadBalancer",
          "request": {
            "url": "http://example.com/api/?Action=CreateLoadBalancer?Name=Name&Scheme=Scheme&SecurityGroups.member.N=SecurityGroups.member.N&Subnets.member.N=Subnets.member.N&Tags.member.N=Tags.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an Application Load Balancer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "19b3e7a2-75ae-478b-b2fc-c714478fcb77"
            }
          ]
        }
      ]
    },
    {
      "name": "Rules",
      "item": [
        {
          "id": "f0a81e59-3910-4fc3-88c1-ae45b0112a25",
          "name": "createRule",
          "request": {
            "url": "http://example.com/api/?Action=CreateRule?Actions.member.N=Actions.member.N&Conditions.member.N=Conditions.member.N&ListenerArn=ListenerArn&Priority=Priority",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a rule for the specified listener."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2a3c5aaa-0169-407f-b0f3-ceaefa30e8cd"
            }
          ]
        }
      ]
    },
    {
      "name": "Target Groups",
      "item": [
        {
          "id": "5a0c6345-abcb-4741-a8b2-522fe36c9e5d",
          "name": "createTargetGroup",
          "request": {
            "url": "http://example.com/api/?Action=CreateTargetGroup?HealthCheckIntervalSeconds=HealthCheckIntervalSeconds&HealthCheckPath=HealthCheckPath&HealthCheckPort=HealthCheckPort&HealthCheckProtocol=HealthCheckProtocol&HealthCheckTimeoutSeconds=HealthCheckTimeoutSeconds&HealthyThresholdCount=HealthyThresholdCount&Matcher=Matcher&Name=Name&Port=Port&Protocol=Protocol&UnhealthyThresholdCount=UnhealthyThresholdCount&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a target group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f3adaa0-453a-4441-a65f-11e76d035bed"
            }
          ]
        }
      ]
    }
  ]
}