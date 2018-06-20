{
  "info": {
    "name": "AWS OpsWorks API Describe Stacks",
    "_postman_id": "f78aec04-fb2d-452a-b23f-5ad08009d328",
    "description": "Requests a description of one or more stacks.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Instances",
      "item": [
        {
          "id": "a1849fd2-c884-4cb9-82dd-dc8eb1499c46",
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
              "id": "86d53e5e-1535-4add-8302-87392a7e7d18"
            }
          ]
        },
        {
          "id": "a82ab7cf-21fa-4e3a-9ad7-e5e37d47f1c9",
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
              "id": "75642a08-ac06-44a4-9971-5ce6706c3844"
            }
          ]
        },
        {
          "id": "ea3539c2-4226-421e-90bd-3a225dc3fb2f",
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
              "id": "0fc785d1-dc3e-4bec-ab1d-3559cdc5db39"
            }
          ]
        },
        {
          "id": "5d7e3591-291e-4edc-b3d5-ec830ac7a0c8",
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
              "id": "0f7b1508-feae-469c-994e-d27e0d7f4a73"
            }
          ]
        },
        {
          "id": "446a03b6-f3d0-4827-b9b3-33419c4effde",
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
              "id": "28f7aebd-7890-483b-9a3b-518a48ba77a8"
            }
          ]
        },
        {
          "id": "7f8ba5c2-2885-4753-8292-95af20bad950",
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
              "id": "335ff605-3c16-4610-bae1-177b6eb2cdd9"
            }
          ]
        },
        {
          "id": "66bb32dd-2b75-48bb-9d3c-0ea5ad481bdc",
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
              "id": "52c710a7-6260-4c94-abbe-674bdaf0c403"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "8f35dd4b-13b6-4151-b59f-414e4231fac0",
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
              "id": "a2390d07-27a7-4aa5-b3fd-1a8bdc54deb5"
            }
          ]
        },
        {
          "id": "0be8bb9f-e098-4100-911a-a90bdde47c52",
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
              "id": "bd6d3aa4-41e6-4e32-9222-45f7c0478e68"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Addresses",
      "item": [
        {
          "id": "db5d8bbf-ac48-4b82-be17-1bd7372ecc97",
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
              "id": "845d6996-2b2e-4790-bc96-8946fbab3554"
            }
          ]
        },
        {
          "id": "7c18c75e-1161-44d1-b45c-8e378e6c4aa6",
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
              "id": "dbea1c4a-c99f-4664-854f-4e9f3ae48607"
            }
          ]
        },
        {
          "id": "01a055b5-c476-4eee-bf10-c669a6f90186",
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
              "id": "1ae3fced-244e-42ec-b8eb-fc7b34b94922"
            }
          ]
        }
      ]
    },
    {
      "name": "Load Balancers",
      "item": [
        {
          "id": "12876075-851c-4988-a1d3-11e7d7af15b0",
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
              "id": "60369f1b-244c-411a-9774-c6b90b9a3db3"
            }
          ]
        },
        {
          "id": "fca7f0b9-e695-4bec-9598-dcadadd8a9e2",
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
              "id": "29cde16e-baa1-4ab8-aa30-01e1523d327f"
            }
          ]
        }
      ]
    },
    {
      "name": "Stacks",
      "item": [
        {
          "id": "4666a2e4-0f21-4349-afe9-42899dabfcdd",
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
              "id": "f0b2761b-dbe3-42e5-852a-bca3421ec29c"
            }
          ]
        },
        {
          "id": "6ff5b630-06f0-4985-a332-b1249e330eea",
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
              "id": "2f574496-6ea3-4100-b7db-dc2794fc69ec"
            }
          ]
        },
        {
          "id": "a456ab5f-5b40-4e69-a93b-9de147372d54",
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
              "id": "051157c6-fbf1-4566-9ce1-e3ec2ad721e6"
            }
          ]
        }
      ]
    },
    {
      "name": "Applications",
      "item": [
        {
          "id": "c2fc63c5-ade0-4ac1-a1a0-59f51ee1801f",
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
              "id": "51cd4464-cfa1-4cba-a2ef-989b58aa7d7a"
            }
          ]
        },
        {
          "id": "1ea6d995-7381-4e1e-94dc-c6db5f9fcd60",
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
              "id": "89c0b464-ced4-4b6b-b369-0f72217f30d4"
            }
          ]
        },
        {
          "id": "156c1bea-e8bd-4b59-b8b1-e57f4604f3a5",
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
              "id": "e40abfbf-76d0-49f2-a8a9-966830848638"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "ad7db3f9-e3db-4a75-a249-c19ee8941a6e",
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
              "id": "49028d82-87bd-4f18-8ff3-353a92c8847f"
            }
          ]
        },
        {
          "id": "b23f738f-c2a4-4a53-ae53-46cfc8a14e45",
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
              "id": "75a87553-29c8-4fdd-bf18-7e0388cc9706"
            }
          ]
        },
        {
          "id": "dfb1a607-743e-42dd-a456-d373e000cdde",
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
              "id": "75e9da03-7c03-4ca4-ab3a-b3ddb59bd5a1"
            }
          ]
        },
        {
          "id": "d05781da-7a78-43a5-b781-7e126a3922ab",
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
              "id": "3c954d01-0892-4925-8544-409ebea0faac"
            }
          ]
        },
        {
          "id": "e5884517-2712-4894-9f1e-c5e957a49dcb",
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
              "id": "6e5eea61-75c9-4537-8a49-29d23828de6f"
            }
          ]
        },
        {
          "id": "b26f8b07-feea-465d-983e-f9841bc6ec8e",
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
              "id": "49064796-2720-4e2f-a159-08eb004045fe"
            }
          ]
        },
        {
          "id": "bb749529-6dd7-49dd-baa7-655878abe752",
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
              "id": "ae22f48e-8e62-46c9-af83-bdcc3988a274"
            }
          ]
        },
        {
          "id": "cc4195b5-a25d-40a1-91b1-f4b3bd1cab2a",
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
              "id": "05cae0c4-72a0-4f41-9cb3-a93e1165ed3e"
            }
          ]
        }
      ]
    },
    {
      "name": "Agent Versions",
      "item": [
        {
          "id": "60b8e2b1-67f8-4e26-9379-f0489b83fd06",
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
              "id": "9f3a452b-8c6f-4a08-b5c1-dd559e17a771"
            }
          ]
        }
      ]
    },
    {
      "name": "Commands",
      "item": [
        {
          "id": "47841e69-2d1a-4647-94db-4300cefd6fe6",
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
              "id": "11bde4a3-fee6-41ff-b8eb-2451d6bb8318"
            }
          ]
        }
      ]
    },
    {
      "name": "Deployments",
      "item": [
        {
          "id": "57317869-ea23-40a9-b153-e3f08c444154",
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
              "id": "53d844bc-e713-4fc2-95ac-8fc6789f7fc9"
            }
          ]
        }
      ]
    },
    {
      "name": "ECS Clusters",
      "item": [
        {
          "id": "cc2c910a-b795-4700-99ac-9ea1501e3a02",
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
              "id": "98978418-9391-4cb9-ae12-d59fb058996c"
            }
          ]
        }
      ]
    },
    {
      "name": "Layers",
      "item": [
        {
          "id": "5a3730ea-fe47-4d6d-bdf0-da9e2ec92421",
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
              "id": "e1094e77-6dae-423a-ba95-cc25b3e51471"
            }
          ]
        }
      ]
    },
    {
      "name": "Auto Scaling",
      "item": [
        {
          "id": "246cd786-921a-4cf1-9155-68225ea21268",
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
              "id": "2eacd95a-20ab-40f8-a41c-2f77265ce33a"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "2dd55d69-7230-4a79-9e99-e31ef8d71a44",
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
              "id": "4b117d88-ad9b-4179-b0d7-f9f55323220d"
            }
          ]
        }
      ]
    },
    {
      "name": "Permissions",
      "item": [
        {
          "id": "1736e0b8-3d2a-4094-a047-0d3bc06f1aea",
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
              "id": "b7c10372-0a00-483a-ac7b-b1cc8f7a4ea5"
            }
          ]
        }
      ]
    },
    {
      "name": "Raid Arrays",
      "item": [
        {
          "id": "2e273b49-1e71-4753-882e-9dd0509a1723",
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
              "id": "b4130b05-848c-46f2-8642-44a4dd752565"
            }
          ]
        }
      ]
    },
    {
      "name": "Service Errors",
      "item": [
        {
          "id": "03f50c49-27f7-4a68-8ff6-e4e9d912d042",
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
              "id": "403f3688-1310-49e4-b8a8-68dfa4660367"
            }
          ]
        }
      ]
    }
  ]
}