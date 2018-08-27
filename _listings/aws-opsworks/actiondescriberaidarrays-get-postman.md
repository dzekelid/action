{
  "info": {
    "name": "AWS OpsWorks API Describe Raid Arrays",
    "_postman_id": "8b637801-84fb-466c-b3ca-41017a5f59ca",
    "description": "Describe an instance's RAID arrays.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Instances",
      "item": [
        {
          "id": "1d4a2fdc-eb16-4d05-8b89-9e3edccb3cdc",
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
              "id": "840e7311-079b-44fd-9585-5060b28d5c51"
            }
          ]
        },
        {
          "id": "83b1af27-6a2d-4387-bee7-d191dc036aeb",
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
              "id": "952b65f0-f712-494c-bb1b-d3ac948b0f5d"
            }
          ]
        },
        {
          "id": "9e330669-fa01-4339-8987-26a4442cd5f9",
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
              "id": "756308ab-387e-4bab-9aa2-fdd2193bca05"
            }
          ]
        },
        {
          "id": "7b6c4a69-4e5b-4f00-877a-a20591110bd3",
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
              "id": "4d5ca82b-40da-4078-9a96-f7abc312a154"
            }
          ]
        },
        {
          "id": "0e35705f-3948-4165-91ee-4dd161e00e29",
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
              "id": "f918ad3e-6e1a-4e8d-a73f-adcf765553f3"
            }
          ]
        },
        {
          "id": "d36948ea-7b7b-424c-ab00-a500922a1c63",
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
              "id": "92a637b5-5e48-415d-9ef4-422c3757af64"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "b465ba3f-155c-4bb7-bd76-0e802abb8a23",
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
              "id": "32b655c2-1a33-4ddd-8512-54691cba5b6c"
            }
          ]
        },
        {
          "id": "a799d29a-31b3-441b-bd66-5a8f100d1627",
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
              "id": "2ff15829-8032-4442-9bd6-34cefbc59f2a"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Addresses",
      "item": [
        {
          "id": "bde2a805-6220-42dc-827a-8d507d407ee9",
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
              "id": "29f53a29-a4e9-4721-bdfb-5eab9c0202b2"
            }
          ]
        },
        {
          "id": "3c1c8907-8350-40ca-8148-cfffe1215e78",
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
              "id": "b22a5a98-0f77-4363-bc97-d7e7398fbfdd"
            }
          ]
        },
        {
          "id": "4552403f-d900-4535-a1b1-fc7942560476",
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
              "id": "9eed3ad8-8ba8-44ef-98d6-b91254e0b8a3"
            }
          ]
        }
      ]
    },
    {
      "name": "Load Balancers",
      "item": [
        {
          "id": "b6850123-0b6f-4ada-b4be-cf4f8eab7c8f",
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
              "id": "ed0215b3-58f2-417f-ab55-d5da0434f2fb"
            }
          ]
        },
        {
          "id": "437767e9-bdd6-4738-82a1-6f44986f2a70",
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
              "id": "9b71111f-4f46-4325-ae1b-78b85220a4e0"
            }
          ]
        }
      ]
    },
    {
      "name": "Stacks",
      "item": [
        {
          "id": "3ca80d6b-e9a3-4d93-be36-4e03dd74b390",
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
              "id": "a558fa0e-3f5c-41da-9b68-53bf887de0b2"
            }
          ]
        }
      ]
    },
    {
      "name": "Applications",
      "item": [
        {
          "id": "e333f446-cfca-404b-b89a-be51d97dd0d5",
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
              "id": "c8af093e-e40c-45d9-a722-c70986c8e0bb"
            }
          ]
        },
        {
          "id": "4d06e756-6061-4796-827a-490083b7935c",
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
              "id": "690705b1-bb58-4040-a343-e754e3f7a8f7"
            }
          ]
        },
        {
          "id": "dfb6d3c4-fd21-41a5-99b3-1428fdf1923f",
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
              "id": "553ddbbc-ead1-49c5-acea-95524ad931f4"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "fa22b440-d3da-4823-9979-6954af8006f2",
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
              "id": "16a95d33-c1b2-4a13-9f71-8983ca596fc0"
            }
          ]
        },
        {
          "id": "632f68b9-9609-4ebe-a128-54161dc66453",
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
              "id": "bd572911-aa92-4e3e-b565-c9e289c58104"
            }
          ]
        },
        {
          "id": "eea6fddc-a364-49f9-a41b-31d77937a93e",
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
              "id": "0b4e9108-97b6-46d1-af8d-3640563f640c"
            }
          ]
        },
        {
          "id": "b94ea7a9-4982-410d-b0c5-53dd25586b9c",
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
              "id": "f77c86f9-32e6-4ce9-afb6-f8adbcf52a22"
            }
          ]
        },
        {
          "id": "8800db2e-7014-4898-8853-eae6d49ab80c",
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
              "id": "48db5f7e-904f-41ff-830f-5285aafe1281"
            }
          ]
        },
        {
          "id": "b5af15d7-b07c-4b91-a722-49fc7627061f",
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
              "id": "dcfbc0b6-c14c-4630-b11d-361e2ffadc43"
            }
          ]
        },
        {
          "id": "3aebb083-9708-43a6-a178-b0635142fc12",
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
              "id": "86ac0ce3-3e24-4560-9bb0-4ea7e1f798a0"
            }
          ]
        },
        {
          "id": "9d9319a3-b97e-4603-80fe-7873f254ddb1",
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
              "id": "019ee049-97a5-46dc-b8b1-d2cbe2227b14"
            }
          ]
        }
      ]
    },
    {
      "name": "Agent Versions",
      "item": [
        {
          "id": "bea7a27d-fcb4-46f4-ba35-facb9c299502",
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
              "id": "b502c749-3957-4b94-b5c3-f44f77bed899"
            }
          ]
        }
      ]
    },
    {
      "name": "Commands",
      "item": [
        {
          "id": "56cca858-cc35-4ae6-a68a-d78c50b849c2",
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
              "id": "68ccc08e-85c1-4e11-a90f-e0a465a34b81"
            }
          ]
        }
      ]
    },
    {
      "name": "Deployments",
      "item": [
        {
          "id": "97c8750c-c862-41b8-9139-004c42d40cb0",
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
              "id": "c61290ee-96c2-4de7-b587-f155710d2f5c"
            }
          ]
        }
      ]
    },
    {
      "name": "ECS Clusters",
      "item": [
        {
          "id": "24ebf95c-1b1e-4c14-8b56-e439088ff2ee",
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
              "id": "77e9516a-d5ce-4d1b-9e03-d65c4ecf6198"
            }
          ]
        }
      ]
    },
    {
      "name": "Layers",
      "item": [
        {
          "id": "8fad8118-4ec3-4d20-a515-b02832f8640c",
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
              "id": "3a600d5b-22e2-4113-bdb5-30653c6a9440"
            }
          ]
        }
      ]
    },
    {
      "name": "Auto Scaling",
      "item": [
        {
          "id": "15552d18-f07d-4a7c-97aa-7f0618e2fb4d",
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
              "id": "c60c4333-0380-4314-83f5-b62e7b4ab55f"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "d75d92b8-c301-4d79-b548-8bd94efc337f",
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
              "id": "df039072-cfc4-4ec7-bd63-07e7d5e3247d"
            }
          ]
        }
      ]
    },
    {
      "name": "Permissions",
      "item": [
        {
          "id": "26b512b4-9fda-4344-9d2f-37e9cd3d0677",
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
              "id": "481cde56-e9f1-4c89-aaa0-7c19c6154985"
            }
          ]
        }
      ]
    },
    {
      "name": "Raid Arrays",
      "item": [
        {
          "id": "9bd2bb73-6b64-44b4-851b-fdfc74f2b9f1",
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
              "id": "d31b24b6-d3a7-4990-99b9-4b8c0d731fba"
            }
          ]
        }
      ]
    }
  ]
}