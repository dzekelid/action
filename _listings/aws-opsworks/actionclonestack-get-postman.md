{
  "info": {
    "name": "AWS OpsWorks API Clone Stack",
    "_postman_id": "ce6d54a1-2a21-4007-9214-13560db44668",
    "description": "Creates a clone of a specified stack.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Instances",
      "item": [
        {
          "id": "fd61170f-afd2-4c3b-99e3-d8e8c13c049e",
          "name": "assignInstance",
          "request": {
            "url": "http://example.com/api/?Action=AssignInstance?InstanceId=InstanceId&LayerIds=LayerIds",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assign a registered instance to a layer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31d73e39-f5a9-4ac9-92e7-cb35732df996"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "a82d0b2c-a275-442f-8649-49ccab9673a7",
          "name": "assignVolume",
          "request": {
            "url": "http://example.com/api/?Action=AssignVolume?InstanceId=InstanceId&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assigns one of the stack's registered Amazon EBS volumes to a specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a92f2a78-d3af-417f-bc21-999a5393e647"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Addresses",
      "item": [
        {
          "id": "3bf64111-73c4-4796-9cfa-72cdf72343e4",
          "name": "associateElasticIp",
          "request": {
            "url": "http://example.com/api/?Action=AssociateElasticIp?ElasticIp=ElasticIp&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates one of the stack's registered Elastic IP addresses with a specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f5e709d5-9fee-42f8-b1d7-3d2144a9acf7"
            }
          ]
        }
      ]
    },
    {
      "name": "Load Balancers",
      "item": [
        {
          "id": "ae3849a3-8333-4b77-9c0c-210df3f35a49",
          "name": "attachElasticLoadBalancer",
          "request": {
            "url": "http://example.com/api/?Action=AttachElasticLoadBalancer?ElasticLoadBalancerName=ElasticLoadBalancerName&LayerId=LayerId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches an Elastic Load Balancing load balancer to a specified layer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e02829ea-6e93-42b3-bea4-7aeb2ebc058a"
            }
          ]
        }
      ]
    },
    {
      "name": "Stacks",
      "item": [
        {
          "id": "e2e79deb-da06-4ae7-9480-25485eb71bb4",
          "name": "cloneStack",
          "request": {
            "url": "http://example.com/api/?Action=CloneStack?AgentVersion=AgentVersion&Attributes=Attributes&ChefConfiguration=ChefConfiguration&CloneAppIds=CloneAppIds&ClonePermissions=ClonePermissions&ConfigurationManager=ConfigurationManager&CustomCookbooksSource=CustomCookbooksSource&CustomJson=CustomJson&DefaultAvailabilityZone=DefaultAvailabilityZone&DefaultInstanceProfileArn=DefaultInstanceProfileArn&DefaultOs=DefaultOs&DefaultRootDeviceType=DefaultRootDeviceType&DefaultSshKeyName=DefaultSshKeyName&DefaultSubnetId=DefaultSubnetId&HostnameTheme=HostnameTheme&Name=Name&Region=Region&ServiceRoleArn=ServiceRoleArn&SourceStackId=SourceStackId&UseCustomCookbooks=UseCustomCookbooks&UseOpsworksSecurityGroups=UseOpsworksSecurityGroups&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a clone of a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "589c6d52-4ff5-4913-acb3-5ede35d54a63"
            }
          ]
        }
      ]
    }
  ]
}