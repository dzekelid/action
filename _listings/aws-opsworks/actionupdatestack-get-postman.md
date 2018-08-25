{
  "info": {
    "name": "AWS OpsWorks API Update Stack",
    "_postman_id": "842da992-7f7f-4dab-8bcf-cbbf2f04eabf",
    "description": "Updates a specified stack.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Instances",
      "item": [
        {
          "id": "33324bdf-776e-4303-9a73-aab5ca2af5b7",
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
              "id": "5f71ef21-1db3-47d3-9c6e-bd59ba075f4c"
            }
          ]
        },
        {
          "id": "559cd051-cb01-4a7a-9e24-69b66dd21603",
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
              "id": "1b431485-790b-4e4f-bd09-74eeca271554"
            }
          ]
        },
        {
          "id": "89f0cd17-d0e2-44bf-b93e-a30c1bd3d44b",
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
              "id": "8205b7a7-d71e-4e42-bb96-fc334315325d"
            }
          ]
        },
        {
          "id": "9528b361-d37a-41d7-bf95-ec06ee4ff005",
          "name": "deregisterInstance",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterInstance?InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregister a registered Amazon EC2 or on-premises instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ebc7789-9bf6-40aa-9b72-388dcab16228"
            }
          ]
        },
        {
          "id": "1162472e-aeaf-4b1b-8f47-99ca205ad8e7",
          "name": "deregisterRdsDbInstance",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterRdsDbInstance?RdsDbInstanceArn=RdsDbInstanceArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregisters an Amazon RDS instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a4d0d41-da5f-4b88-9a2f-b8bdb21a7ad9"
            }
          ]
        },
        {
          "id": "35240ede-1fbd-4717-a386-a92435c5d11c",
          "name": "describeInstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInstances?InstanceIds=InstanceIds&LayerId=LayerId&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a description of a set of instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fc61cc95-3140-49ba-b19e-f26b5c958439"
            }
          ]
        },
        {
          "id": "28a00c21-3fef-4e02-9964-64f518f39973",
          "name": "describeRdsDbInstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRdsDbInstances?RdsDbInstanceArns=RdsDbInstanceArns&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes Amazon RDS instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da7c6ebe-a175-4105-ba38-5593d525efc6"
            }
          ]
        },
        {
          "id": "3954f7ed-26c2-47a5-90dd-e3cf918582a1",
          "name": "rebootInstance",
          "request": {
            "url": "http://example.com/api/?Action=RebootInstance?InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Reboots a specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6b7e3f5-e156-4252-ba5b-064fc2bc623f"
            }
          ]
        },
        {
          "id": "0df841de-ea2d-4440-87a8-e4a1a4a930af",
          "name": "registerInstance",
          "request": {
            "url": "http://example.com/api/?Action=RegisterInstance?Hostname=Hostname&InstanceIdentity=InstanceIdentity&PrivateIp=PrivateIp&PublicIp=PublicIp&RsaPublicKey=RsaPublicKey&RsaPublicKeyFingerprint=RsaPublicKeyFingerprint&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers instances that were created outside of AWS OpsWorks Stacks with a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "609a2345-5545-42b4-9ee5-56e14eb7d54d"
            }
          ]
        },
        {
          "id": "8c9cf594-21cf-4191-a9a1-939a49b12357",
          "name": "registerRdsDbInstance",
          "request": {
            "url": "http://example.com/api/?Action=RegisterRdsDbInstance?DbPassword=DbPassword&DbUser=DbUser&RdsDbInstanceArn=RdsDbInstanceArn&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers an Amazon RDS instance with a stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4d7fb623-4e63-4bb5-b461-e87d96a40ab7"
            }
          ]
        },
        {
          "id": "e9d0c3cd-6192-429f-95a2-7e5c872ed962",
          "name": "startInstance",
          "request": {
            "url": "http://example.com/api/?Action=StartInstance?InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Starts a specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "94b07fcc-eb88-4321-921c-29fa25a020ba"
            }
          ]
        },
        {
          "id": "4b767896-b955-4afc-96e1-54ce9275d42a",
          "name": "stopInstance",
          "request": {
            "url": "http://example.com/api/?Action=StopInstance?InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Stops a specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "699326e2-c04e-4482-abe5-b60679e89478"
            }
          ]
        },
        {
          "id": "16aef57e-205f-44a2-be59-9def4015e2a3",
          "name": "unassignInstance",
          "request": {
            "url": "http://example.com/api/?Action=UnassignInstance?InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unassigns a registered instance from all of it's layers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c81333f-ba5b-4b14-b04f-492131a8e3b1"
            }
          ]
        },
        {
          "id": "dd36efa3-070e-4a95-93bb-3e1c14986565",
          "name": "updateInstance",
          "request": {
            "url": "http://example.com/api/?Action=UpdateInstance?AgentVersion=AgentVersion&AmiId=AmiId&Architecture=Architecture&AutoScalingType=AutoScalingType&EbsOptimized=EbsOptimized&Hostname=Hostname&InstallUpdatesOnBoot=InstallUpdatesOnBoot&InstanceId=InstanceId&InstanceType=InstanceType&LayerIds=LayerIds&Os=Os&SshKeyName=SshKeyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f7b60cf6-c01e-4b5f-ade7-fbf63dbdb41c"
            }
          ]
        },
        {
          "id": "a2f64e3f-2792-4ebd-81d1-04e08ef3bc34",
          "name": "updateRdsDbInstance",
          "request": {
            "url": "http://example.com/api/?Action=UpdateRdsDbInstance?DbPassword=DbPassword&DbUser=DbUser&RdsDbInstanceArn=RdsDbInstanceArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates an Amazon RDS instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "66745998-dc85-4fb1-9a7a-b4d09b95d8fb"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "c4fe568a-23dc-4bd9-ab50-0788271c1e7b",
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
              "id": "85d5fad9-85df-4910-938e-3f8dd5a03a4a"
            }
          ]
        },
        {
          "id": "1149ce11-8878-417a-a9ed-d78b5bc49f35",
          "name": "deregisterVolume",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterVolume?VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregisters an Amazon EBS volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0a236b7d-6c4c-42f0-b712-8061ed42f62e"
            }
          ]
        },
        {
          "id": "474e4f70-a74b-4d97-bc09-21a573a81e2e",
          "name": "describeVolumes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVolumes?InstanceId=InstanceId&RaidArrayId=RaidArrayId&StackId=StackId&VolumeIds=VolumeIds",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes an instance's Amazon EBS volumes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d4b19abf-497e-406b-b41d-8d68e1f42558"
            }
          ]
        },
        {
          "id": "fc481c25-cac4-4ad6-b261-4bb5f62ad6cf",
          "name": "registerVolume",
          "request": {
            "url": "http://example.com/api/?Action=RegisterVolume?Ec2VolumeId=Ec2VolumeId&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers an Amazon EBS volume with a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "68822d23-462e-481a-8240-298d8e409e4e"
            }
          ]
        },
        {
          "id": "0031dcdf-0be0-43f5-bcc0-753d347418cf",
          "name": "unassignVolume",
          "request": {
            "url": "http://example.com/api/?Action=UnassignVolume?VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unassigns an assigned Amazon EBS volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0adb165f-0a9e-4301-b253-53189749b772"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Addresses",
      "item": [
        {
          "id": "80cb62f5-6d40-4b4d-902f-1480919e068f",
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
              "id": "30720b2f-3f19-43a3-9290-fb72bb04e491"
            }
          ]
        },
        {
          "id": "e6f5129b-f72d-4b47-96f6-eb5531d65342",
          "name": "deregisterElasticIp",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterElasticIp?ElasticIp=ElasticIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregisters a specified Elastic IP address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77a85cca-7037-43ea-9757-3c6f04980c41"
            }
          ]
        },
        {
          "id": "869377f3-16fa-468d-bd2a-fe8a424e299a",
          "name": "describeElasticIps",
          "request": {
            "url": "http://example.com/api/?Action=DescribeElasticIps?InstanceId=InstanceId&Ips=Ips&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes Elastic IPs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2a7002f7-af4a-45c5-9b83-dbd67e54fd8c"
            }
          ]
        },
        {
          "id": "8e1c4c7f-b224-43c6-bb3b-534370411684",
          "name": "disassociateElasticIp",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateElasticIp?ElasticIp=ElasticIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates an Elastic IP address from its instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "32732d9a-80a8-495c-9070-761578ca02ec"
            }
          ]
        },
        {
          "id": "3a065a7e-5020-49eb-91b5-4521180104e0",
          "name": "registerElasticIp",
          "request": {
            "url": "http://example.com/api/?Action=RegisterElasticIp?ElasticIp=ElasticIp&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers an Elastic IP address with a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8b6d0b9-de56-415f-92c8-5280f7b195d3"
            }
          ]
        },
        {
          "id": "0926d18d-33c1-45d6-b108-b3087038b310",
          "name": "updateElasticIp",
          "request": {
            "url": "http://example.com/api/?Action=UpdateElasticIp?ElasticIp=ElasticIp&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a registered Elastic IP address's name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f1901a05-7563-49a5-8931-e6c7d3f2f317"
            }
          ]
        }
      ]
    },
    {
      "name": "Load Balancers",
      "item": [
        {
          "id": "4ab5c9b6-bb42-48a8-adc8-1964117bde5c",
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
              "id": "5e84fb16-c7e7-4469-a861-8a21830028c9"
            }
          ]
        },
        {
          "id": "9c13c40e-ca93-4151-bdf7-4820e3ef6545",
          "name": "describeElasticLoadBalancers",
          "request": {
            "url": "http://example.com/api/?Action=DescribeElasticLoadBalancers?LayerIds=LayerIds&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes a stack's Elastic Load Balancing instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "75dbd2a7-1985-4511-a1de-591f489d9f12"
            }
          ]
        },
        {
          "id": "c6e19c52-7fd2-4c56-909c-c85b6705baf0",
          "name": "detachElasticLoadBalancer",
          "request": {
            "url": "http://example.com/api/?Action=DetachElasticLoadBalancer?ElasticLoadBalancerName=ElasticLoadBalancerName&LayerId=LayerId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches a specified Elastic Load Balancing instance from its layer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b976bcf8-1c7d-439d-8cf1-d7f7a638ffc0"
            }
          ]
        }
      ]
    },
    {
      "name": "Stacks",
      "item": [
        {
          "id": "ba8ea6b0-7176-4d3b-8006-ec082f5b5d90",
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
              "id": "74672227-fa4c-4b65-8d93-d4a11a54113a"
            }
          ]
        },
        {
          "id": "a267fc89-c4c7-493d-a5cd-1a1cb7e5d6e9",
          "name": "describeStackProvisioningParameters",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStackProvisioningParameters?StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a description of a stack's provisioning parameters."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "767de9fe-ea75-4ad0-ba8f-7f943007bc0d"
            }
          ]
        },
        {
          "id": "72807c78-8a8a-43e6-acd9-34b1f00004bb",
          "name": "describeStacks",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStacks?StackIds=StackIds",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a description of one or more stacks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0e8a84d-0a7b-4ae1-bdc9-9274e3d6ae8d"
            }
          ]
        },
        {
          "id": "a8736c08-c073-49fa-baab-e555e8b9f7b7",
          "name": "describeStackSummary",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStackSummary?StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the number of layers and apps in a specified stack, and the number of instances in\n      each state, such as running_setup or online."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c636abd-31b0-42d4-8aa6-6cc91894ba6d"
            }
          ]
        },
        {
          "id": "f0641f24-f5a8-4890-bd7b-0bf279bf3690",
          "name": "startStack",
          "request": {
            "url": "http://example.com/api/?Action=StartStack?StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Starts a stack's instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6211b777-e169-4960-ab40-65d4cb4504d2"
            }
          ]
        },
        {
          "id": "9deb0f45-01f3-4cb7-8072-669edda8cad3",
          "name": "stopStack",
          "request": {
            "url": "http://example.com/api/?Action=StopStack?StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Stops a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e4b35d74-4599-4d49-8fa4-32b35b464a7b"
            }
          ]
        },
        {
          "id": "70b42cce-f411-4c89-92e3-be44a9c2ed96",
          "name": "updateStack",
          "request": {
            "url": "http://example.com/api/?Action=UpdateStack?AgentVersion=AgentVersion&Attributes=Attributes&ChefConfiguration=ChefConfiguration&ConfigurationManager=ConfigurationManager&CustomCookbooksSource=CustomCookbooksSource&CustomJson=CustomJson&DefaultAvailabilityZone=DefaultAvailabilityZone&DefaultInstanceProfileArn=DefaultInstanceProfileArn&DefaultOs=DefaultOs&DefaultRootDeviceType=DefaultRootDeviceType&DefaultSshKeyName=DefaultSshKeyName&DefaultSubnetId=DefaultSubnetId&HostnameTheme=HostnameTheme&Name=Name&ServiceRoleArn=ServiceRoleArn&StackId=StackId&UseCustomCookbooks=UseCustomCookbooks&UseOpsworksSecurityGroups=UseOpsworksSecurityGroups",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "22f90df3-d319-48a6-be14-d6c821bf585c"
            }
          ]
        }
      ]
    },
    {
      "name": "Applications",
      "item": [
        {
          "id": "f17713b6-a860-46d8-a284-6f5aa2e7fb50",
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
              "id": "8fe9141a-b9b7-470d-bbc0-225d7bf8bd8d"
            }
          ]
        },
        {
          "id": "2c529296-4a91-4c2b-b8c3-df0eb1013e5e",
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
              "id": "ff52b6ea-5ee9-4cfd-81d3-9f56eeb0f631"
            }
          ]
        },
        {
          "id": "b2ee28f7-2505-41c9-835c-4ea93c09b210",
          "name": "describeApps",
          "request": {
            "url": "http://example.com/api/?Action=DescribeApps?AppIds=AppIds&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a description of a specified set of apps."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6ed7adb5-cd9f-45d5-bf2f-87634c51c1d3"
            }
          ]
        },
        {
          "id": "6e3feace-26c5-42c9-bc98-4d83cbd3b4bc",
          "name": "updateApp",
          "request": {
            "url": "http://example.com/api/?Action=UpdateApp?AppId=AppId&AppSource=AppSource&Attributes=Attributes&DataSources=DataSources&Description=Description&Domains=Domains&EnableSsl=EnableSsl&Environment=Environment&Name=Name&SslConfiguration=SslConfiguration&Type=Type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a specified app."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "52e6a4e2-b997-4f4f-84ed-d82c9bbbc7cc"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "86175497-e180-4cfc-a2c3-e41b6d51513f",
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
              "id": "8184f275-6fb8-4fb2-80cd-ff8b4756b48c"
            }
          ]
        },
        {
          "id": "ef106a0b-5b42-4a14-bed8-8aaca372c0e9",
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
              "id": "e58d2e6d-e468-4c91-a1b1-d2d7c029de86"
            }
          ]
        },
        {
          "id": "24f89631-d233-4a8d-b01a-8bf229f5f636",
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
              "id": "8d714d89-51f2-42cc-8d65-396a8c32d028"
            }
          ]
        },
        {
          "id": "d92f02e3-6e9c-4cd3-9e41-76a0ca9e8b82",
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
              "id": "fdaf75f8-7749-479f-8b62-d9132ecf5dd6"
            }
          ]
        },
        {
          "id": "235023aa-bcde-4424-8672-536b18fc37d6",
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
              "id": "78c26ed1-6746-4623-ade1-9081267c1cf0"
            }
          ]
        },
        {
          "id": "4812a5a0-35ae-47f7-a761-1b5f907ead61",
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
              "id": "82272190-5538-47ad-8420-8bf9cfcd0832"
            }
          ]
        },
        {
          "id": "d2c1a4a9-7f2a-4c47-b4ec-db9c30461efa",
          "name": "deleteUserProfile",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUserProfile?IamUserArn=IamUserArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a user profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ba42c6f-4899-4a74-b9c5-3163e897a106"
            }
          ]
        },
        {
          "id": "0f4e2ce9-b815-42cd-a119-7987adf4f243",
          "name": "deregisterEcsCluster",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterEcsCluster?EcsClusterArn=EcsClusterArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregisters a specified Amazon ECS cluster from a stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3073e21c-61c8-4393-bfa1-889753588899"
            }
          ]
        }
      ]
    },
    {
      "name": "Agent Versions",
      "item": [
        {
          "id": "8f6fd511-ea8c-45d6-8543-2260f549047f",
          "name": "describeAgentVersions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAgentVersions?ConfigurationManager=ConfigurationManager&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the available AWS OpsWorks Stacks agent versions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3d555e33-d9c8-4642-8175-671b5166622c"
            }
          ]
        }
      ]
    },
    {
      "name": "Commands",
      "item": [
        {
          "id": "9cb58b80-6a5c-4b04-9e11-0e2c9fe18107",
          "name": "describeCommands",
          "request": {
            "url": "http://example.com/api/?Action=DescribeCommands?CommandIds=CommandIds&DeploymentId=DeploymentId&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the results of specified commands."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c63ba99-7df0-44a3-9215-9465dbf96100"
            }
          ]
        }
      ]
    },
    {
      "name": "Deployments",
      "item": [
        {
          "id": "7ceef943-a621-452f-bfc6-b378d69b1724",
          "name": "describeDeployments",
          "request": {
            "url": "http://example.com/api/?Action=DescribeDeployments?AppId=AppId&DeploymentIds=DeploymentIds&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a description of a specified set of deployments."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f14e8cb5-35fb-47d7-bbb3-9ff4d5c96212"
            }
          ]
        }
      ]
    },
    {
      "name": "ECS Clusters",
      "item": [
        {
          "id": "f4b41876-1a50-417c-864f-cff24f9704f7",
          "name": "describeEcsClusters",
          "request": {
            "url": "http://example.com/api/?Action=DescribeEcsClusters?EcsClusterArns=EcsClusterArns&MaxResults=MaxResults&NextToken=NextToken&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes Amazon ECS clusters that are registered with a stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b251cf5-2ee3-46ac-9ceb-3aff3900075e"
            }
          ]
        },
        {
          "id": "73c8c24f-4d4e-45dd-9c44-115293f7183d",
          "name": "registerEcsCluster",
          "request": {
            "url": "http://example.com/api/?Action=RegisterEcsCluster?EcsClusterArn=EcsClusterArn&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers a specified Amazon ECS cluster with a stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "39bb405e-0e4d-4b77-ad3e-08bcb56c1d7e"
            }
          ]
        }
      ]
    },
    {
      "name": "Layers",
      "item": [
        {
          "id": "1b349123-2858-4f48-8d20-5a8046273270",
          "name": "describeLayers",
          "request": {
            "url": "http://example.com/api/?Action=DescribeLayers?LayerIds=LayerIds&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a description of one or more layers in a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1864e21b-866e-43fd-8439-b21f95293b86"
            }
          ]
        },
        {
          "id": "be1922e6-c938-4cf6-9510-7c3a90453f27",
          "name": "updateLayer",
          "request": {
            "url": "http://example.com/api/?Action=UpdateLayer?Attributes=Attributes&AutoAssignElasticIps=AutoAssignElasticIps&AutoAssignPublicIps=AutoAssignPublicIps&CustomInstanceProfileArn=CustomInstanceProfileArn&CustomJson=CustomJson&CustomRecipes=CustomRecipes&CustomSecurityGroupIds=CustomSecurityGroupIds&EnableAutoHealing=EnableAutoHealing&InstallUpdatesOnBoot=InstallUpdatesOnBoot&LayerId=LayerId&LifecycleEventConfiguration=LifecycleEventConfiguration&Name=Name&Packages=Packages&Shortname=Shortname&UseEbsOptimizedInstances=UseEbsOptimizedInstances&VolumeConfigurations=VolumeConfigurations",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a specified layer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b7e5fd88-f02c-4964-addf-5f2a03fa3d20"
            }
          ]
        }
      ]
    },
    {
      "name": "Auto Scaling",
      "item": [
        {
          "id": "c7405138-2b23-44dc-808c-363facdace75",
          "name": "describeLoadBasedAutoScaling",
          "request": {
            "url": "http://example.com/api/?Action=DescribeLoadBasedAutoScaling?LayerIds=LayerIds",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes load-based auto scaling configurations for specified layers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69bd701f-ea07-47c6-983d-bedf87e12dcf"
            }
          ]
        },
        {
          "id": "efb7f048-12b7-4f0c-8775-f157ccda8b61",
          "name": "describeTimeBasedAutoScaling",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTimeBasedAutoScaling?InstanceIds=InstanceIds",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes time-based auto scaling configurations for specified instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3d98563-b416-44af-b157-3e3f486943a3"
            }
          ]
        },
        {
          "id": "e699ba7b-0d88-4909-9049-5248987c7606",
          "name": "setLoadBasedAutoScaling",
          "request": {
            "url": "http://example.com/api/?Action=SetLoadBasedAutoScaling?DownScaling=DownScaling&Enable=Enable&LayerId=LayerId&UpScaling=UpScaling",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Specify the load-based auto scaling configuration for a specified layer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "059863f7-d681-4268-b5a5-fa4d32c16b2b"
            }
          ]
        },
        {
          "id": "9a8cadf3-02c6-417f-9ad9-4347a7014fdb",
          "name": "setTimeBasedAutoScaling",
          "request": {
            "url": "http://example.com/api/?Action=SetTimeBasedAutoScaling?AutoScalingSchedule=AutoScalingSchedule&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Specify the time-based auto scaling configuration for a specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "19b2b896-e959-4a31-a25a-b7ed25da1877"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "a8e88989-06b9-452c-890c-4905f0c0b314",
          "name": "describeMyUserProfile",
          "request": {
            "url": "http://example.com/api/?Action=DescribeMyUserProfile?UserProfile=UserProfile",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes a user's SSH information."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5017a83c-1c2e-4444-9dc9-3113adca390d"
            }
          ]
        },
        {
          "id": "4a227920-0467-4f8f-9d75-ae016cce135b",
          "name": "describeUserProfiles",
          "request": {
            "url": "http://example.com/api/?Action=DescribeUserProfiles?IamUserArns=IamUserArns",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describe specified users."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b380c22-8f1d-4e2b-8911-26c6ea54d53f"
            }
          ]
        },
        {
          "id": "dd647636-99fa-4751-980d-544b257767c2",
          "name": "updateMyUserProfile",
          "request": {
            "url": "http://example.com/api/?Action=UpdateMyUserProfile?SshPublicKey=SshPublicKey",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a user's SSH public key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb11b0ba-3056-4b48-9e05-7e2bd2faedd6"
            }
          ]
        }
      ]
    },
    {
      "name": "Permissions",
      "item": [
        {
          "id": "30d2e4ff-9bfc-45b3-af78-b416ad4314f9",
          "name": "describePermissions",
          "request": {
            "url": "http://example.com/api/?Action=DescribePermissions?IamUserArn=IamUserArn&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the permissions for a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "70cc1b17-9fab-4ccf-9083-841a98447dc3"
            }
          ]
        },
        {
          "id": "e9f0365f-6b27-44b0-9de1-c1920242872d",
          "name": "setPermission",
          "request": {
            "url": "http://example.com/api/?Action=SetPermission?AllowSsh=AllowSsh&AllowSudo=AllowSudo&IamUserArn=IamUserArn&Level=Level&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Specifies a user's permissions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e5c936a7-ded3-4ba9-9ddc-1c1f0a4ce54d"
            }
          ]
        }
      ]
    },
    {
      "name": "Raid Arrays",
      "item": [
        {
          "id": "7e134758-a3ae-43e9-aba2-f7202be4ed5b",
          "name": "describeRaidArrays",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRaidArrays?InstanceId=InstanceId&RaidArrayIds=RaidArrayIds&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describe an instance's RAID arrays."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5011f688-3b11-4a37-8a55-3781a223c6a4"
            }
          ]
        }
      ]
    },
    {
      "name": "Service Errors",
      "item": [
        {
          "id": "bf59a104-9130-4ba0-9cd4-22f47a2414f9",
          "name": "describeServiceErrors",
          "request": {
            "url": "http://example.com/api/?Action=DescribeServiceErrors?InstanceId=InstanceId&ServiceErrorIds=ServiceErrorIds&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes AWS OpsWorks Stacks service errors."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5088843d-e532-4763-9d9d-62eb9504eeb7"
            }
          ]
        }
      ]
    },
    {
      "name": "Host Names",
      "item": [
        {
          "id": "8ce6acf9-b6cf-42af-b8fe-dfc716a1f06a",
          "name": "getHostnameSuggestion",
          "request": {
            "url": "http://example.com/api/?Action=GetHostnameSuggestion?LayerId=LayerId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a generated host name for the specified layer, based on the current host name theme."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e80ca30d-20b8-42fb-9cde-744c24172052"
            }
          ]
        }
      ]
    },
    {
      "name": "Access",
      "item": [
        {
          "id": "a236abf5-ef8b-4a22-a827-48fdf7fd467e",
          "name": "grantAccess",
          "request": {
            "url": "http://example.com/api/?Action=GrantAccess?InstanceId=InstanceId&ValidForInMinutes=ValidForInMinutes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "NoteThis action can be used only with Windows stacks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eb604a61-26a3-4173-a463-407c570325ad"
            }
          ]
        }
      ]
    }
  ]
}