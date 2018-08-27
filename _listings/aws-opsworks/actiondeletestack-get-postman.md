{
  "info": {
    "name": "AWS OpsWorks API Delete Stack",
    "_postman_id": "fb4346ad-dc67-4686-820c-9a6a634a2e46",
    "description": "Deletes a specified stack.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Instances",
      "item": [
        {
          "id": "d98cfff5-dfe0-4eff-86b0-24d8be68291d",
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
              "id": "9984f289-cfb1-4af5-b19c-7f40011aa413"
            }
          ]
        },
        {
          "id": "1f422d0e-beea-4d67-b467-bb26ced6932e",
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
              "id": "1f3ae2a8-95b1-4a37-8bc5-13e6bba7ef9a"
            }
          ]
        },
        {
          "id": "eadf6d8b-391e-40fe-8d59-f0371cb254b6",
          "name": "deleteInstance",
          "request": {
            "url": "http://example.com/api/?Action=DeleteInstance?DeleteElasticIp=DeleteElasticIp&DeleteVolumes=DeleteVolumes&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specified instance, which terminates the associated Amazon EC2 instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "28e6ee8a-d571-4e48-93ac-6e46176b0b16"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "81484315-7791-4aa9-9d0e-959d9057adf8",
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
              "id": "88291e2c-f6f4-4003-bdc9-e8618be664e4"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Addresses",
      "item": [
        {
          "id": "79a7940b-f0a6-4489-a020-7ec8b5597611",
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
              "id": "14b52201-10c2-49fb-8b84-7e1589d9810e"
            }
          ]
        }
      ]
    },
    {
      "name": "Load Balancers",
      "item": [
        {
          "id": "e6f34b59-e819-41b5-8f87-61a1a1f0ef61",
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
              "id": "2a31c293-46b4-4dec-a0ed-c6b617a55bfd"
            }
          ]
        }
      ]
    },
    {
      "name": "Stacks",
      "item": [
        {
          "id": "86893fbf-c8f6-42d9-ac4f-236b70504ea7",
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
              "id": "e017af6c-e831-4f9f-8585-3c6a31419441"
            }
          ]
        }
      ]
    },
    {
      "name": "Applications",
      "item": [
        {
          "id": "fa27a361-82a7-48b5-9934-de5a7d2b73fc",
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
              "id": "bac83b3c-42f2-4ff8-8bc4-138ef1c795e1"
            }
          ]
        },
        {
          "id": "81313d04-5e1e-4067-867f-7f145b6ab7e4",
          "name": "deleteApp",
          "request": {
            "url": "http://example.com/api/?Action=DeleteApp?AppId=AppId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specified app."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1651304c-1bcf-41f6-b3f1-e5e30dfb5ef0"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "a809c667-e79d-4e38-954f-d5e511c1db54",
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
              "id": "16267f25-3f12-4e28-aaef-8aa1b8dc66c3"
            }
          ]
        },
        {
          "id": "750a23ca-0fc3-483e-a421-c71e47e2efce",
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
              "id": "53d163d1-0808-424f-b7c7-7ef605ab8b76"
            }
          ]
        },
        {
          "id": "c828e021-af32-48b4-af95-bda24d8d8e7e",
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
              "id": "de30b4b3-8f80-4b7a-a3d5-f6f4c98971b3"
            }
          ]
        },
        {
          "id": "bfe25959-3557-4550-8a1e-bc7ab2b1a468",
          "name": "createUserProfile",
          "request": {
            "url": "http://example.com/api/?Action=CreateUserProfile?AllowSelfManagement=AllowSelfManagement&IamUserArn=IamUserArn&SshPublicKey=SshPublicKey&SshUsername=SshUsername",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new user profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8edbb3f1-a27c-48b2-94ad-62511e7ce04b"
            }
          ]
        },
        {
          "id": "8a9870e2-d468-4435-a210-aad55f85dbef",
          "name": "deleteLayer",
          "request": {
            "url": "http://example.com/api/?Action=DeleteLayer?LayerId=LayerId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specified layer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2a3fae12-9ea7-4d02-944b-f298f18133e0"
            }
          ]
        },
        {
          "id": "6fe99be6-9766-4549-94b3-0d201eb5ed4f",
          "name": "deleteStack",
          "request": {
            "url": "http://example.com/api/?Action=DeleteStack?StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a41f731-8524-44e2-a557-d4be6fd136e5"
            }
          ]
        }
      ]
    }
  ]
}