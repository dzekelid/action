{
  "info": {
    "name": "AWS OpsWorks API Create Stack",
    "_postman_id": "1d6e531b-b65b-4a46-bbb9-1a06d3dfc219",
    "description": "Creates a new stack.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Instances",
      "item": [
        {
          "id": "47bc3036-38f8-4367-9ace-0cb81ff7b75f",
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
              "id": "f676f2e5-aa20-43b8-aa7e-b8f006db267c"
            }
          ]
        },
        {
          "id": "9b2b06fe-589b-4fd6-b61f-3251c8e2cfdb",
          "name": "createInstance",
          "request": {
            "url": "http://example.com/api/?Action=CreateInstance?AgentVersion=AgentVersion&AmiId=AmiId&Architecture=Architecture&AutoScalingType=AutoScalingType&AvailabilityZone=AvailabilityZone&BlockDeviceMappings=BlockDeviceMappings&EbsOptimized=EbsOptimized&Hostname=Hostname&InstallUpdatesOnBoot=InstallUpdatesOnBoot&InstanceType=InstanceType&LayerIds=LayerIds&Os=Os&RootDeviceType=RootDeviceType&SshKeyName=SshKeyName&StackId=StackId&SubnetId=SubnetId&Tenancy=Tenancy&VirtualizationType=VirtualizationType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an instance in a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e55091b5-bf85-4ea2-a07d-ae87e1798b70"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "490b9d96-3ee5-4fb0-93c2-7e9e7686c4a3",
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
              "id": "9c867c02-eacc-441a-9d1a-227b59eb0dae"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Addresses",
      "item": [
        {
          "id": "443d540b-6dbe-4fc8-aee3-cad48a6fe607",
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
              "id": "c19fb817-7378-4f5d-b4fb-13b31abb7aa0"
            }
          ]
        }
      ]
    },
    {
      "name": "Load Balancers",
      "item": [
        {
          "id": "f833abd0-68ed-49a3-aa52-94c8f0737223",
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
              "id": "53e5d07d-d295-46c0-ad82-115885d15087"
            }
          ]
        }
      ]
    },
    {
      "name": "Stacks",
      "item": [
        {
          "id": "f2695d20-a843-426e-aad0-b57335912aff",
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
              "id": "7abd429a-1d2c-4a24-a3ec-69b2f078c11c"
            }
          ]
        }
      ]
    },
    {
      "name": "Applications",
      "item": [
        {
          "id": "c17a2f03-9129-494f-9052-30b182d53602",
          "name": "createApp",
          "request": {
            "url": "http://example.com/api/?Action=CreateApp?AppSource=AppSource&Attributes=Attributes&DataSources=DataSources&Description=Description&Domains=Domains&EnableSsl=EnableSsl&Environment=Environment&Name=Name&Shortname=Shortname&SslConfiguration=SslConfiguration&StackId=StackId&Type=Type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an app for a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1a96c816-3199-45d4-be81-547b7a1a0a46"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "883c13d7-ee99-4226-8db7-a265514f4b60",
          "name": "createDeployment",
          "request": {
            "url": "http://example.com/api/?Action=CreateDeployment?AppId=AppId&Command=Command&Comment=Comment&CustomJson=CustomJson&InstanceIds=InstanceIds&LayerIds=LayerIds&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Runs deployment or stack commands."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a52e4a9-5c44-43f4-8082-3d72fd91a76b"
            }
          ]
        },
        {
          "id": "d0d36378-1dad-4b17-b51e-8bc83d32af2c",
          "name": "createLayer",
          "request": {
            "url": "http://example.com/api/?Action=CreateLayer?Attributes=Attributes&AutoAssignElasticIps=AutoAssignElasticIps&AutoAssignPublicIps=AutoAssignPublicIps&CustomInstanceProfileArn=CustomInstanceProfileArn&CustomJson=CustomJson&CustomRecipes=CustomRecipes&CustomSecurityGroupIds=CustomSecurityGroupIds&EnableAutoHealing=EnableAutoHealing&InstallUpdatesOnBoot=InstallUpdatesOnBoot&LifecycleEventConfiguration=LifecycleEventConfiguration&Name=Name&Packages=Packages&Shortname=Shortname&StackId=StackId&Type=Type&UseEbsOptimizedInstances=UseEbsOptimizedInstances&VolumeConfigurations=VolumeConfigurations",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a layer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d60183b9-b1c7-4f58-9ad2-d6575205d280"
            }
          ]
        },
        {
          "id": "2f6078cb-6f94-4696-84a7-f56faf7e1be1",
          "name": "createStack",
          "request": {
            "url": "http://example.com/api/?Action=CreateStack?AgentVersion=AgentVersion&Attributes=Attributes&ChefConfiguration=ChefConfiguration&ConfigurationManager=ConfigurationManager&CustomCookbooksSource=CustomCookbooksSource&CustomJson=CustomJson&DefaultAvailabilityZone=DefaultAvailabilityZone&DefaultInstanceProfileArn=DefaultInstanceProfileArn&DefaultOs=DefaultOs&DefaultRootDeviceType=DefaultRootDeviceType&DefaultSshKeyName=DefaultSshKeyName&DefaultSubnetId=DefaultSubnetId&HostnameTheme=HostnameTheme&Name=Name&Region=Region&ServiceRoleArn=ServiceRoleArn&UseCustomCookbooks=UseCustomCookbooks&UseOpsworksSecurityGroups=UseOpsworksSecurityGroups&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0bd3f69-696f-44df-afd3-a8bad62c607d"
            }
          ]
        }
      ]
    }
  ]
}