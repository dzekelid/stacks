{
  "info": {
    "name": "AWS AppStream 2.0 API Describe Stacks",
    "_postman_id": "b800e9be-7cbf-40a1-b581-baa93590569b",
    "description": "If stack names are not provided, this operation describes the specified stacks;\n            otherwise, all stacks in the account are described.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Fleet",
      "item": [
        {
          "id": "149f293b-92e5-48c9-a522-9b40ce5bd17b",
          "name": "AssociateFleet",
          "request": {
            "url": "http://example.com/api/?Action=AssociateFleet?FleetName=FleetName&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associate a fleet to a stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e71b5dd-278f-48c1-b8c2-c32b261328cf"
            }
          ]
        },
        {
          "id": "85c3f280-8f67-4a9a-ab91-f9f239f40ae6",
          "name": "CreateFleet",
          "request": {
            "url": "http://example.com/api/?Action=CreateFleet?ComputeCapacity=ComputeCapacity&Description=Description&DisconnectTimeoutInSeconds=DisconnectTimeoutInSeconds&DisplayName=DisplayName&ImageName=ImageName&InstanceType=InstanceType&MaxUserDurationInSeconds=MaxUserDurationInSeconds&Name=Name&VpcConfig=VpcConfig",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new fleet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69dee16f-e80d-4ca7-97cd-67d6e6e42a3c"
            }
          ]
        },
        {
          "id": "0bbfac84-292e-41da-a0c2-69bf707353ef",
          "name": "CreateStack",
          "request": {
            "url": "http://example.com/api/?Action=CreateStack?Description=Description&DisplayName=DisplayName&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Create a new stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "10b98704-e2b8-49d8-bdcb-26977677b243"
            }
          ]
        },
        {
          "id": "1fd9f9c9-d82d-4bbf-a2dc-54cb3859069a",
          "name": "DeleteFleet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteFleet?Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a fleet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b26588a7-dc73-4e18-8400-b2507be27085"
            }
          ]
        },
        {
          "id": "3edfdaba-c655-41c1-9671-2b4b238a5b32",
          "name": "DescribeFleets",
          "request": {
            "url": "http://example.com/api/?Action=DescribeFleets?Names=Names&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "If fleet names are provided, this operation describes the specified fleets;\n            otherwise, all the fleets in the account are described."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "116ead80-a93f-40e6-abae-3898f263ea24"
            }
          ]
        }
      ]
    },
    {
      "name": "URL",
      "item": [
        {
          "id": "c529be0d-d2d4-4517-9a27-84c42476d108",
          "name": "CreateStreamingURL",
          "request": {
            "url": "http://example.com/api/?Action=CreateStreamingURL?ApplicationId=ApplicationId&FleetName=FleetName&SessionContext=SessionContext&StackName=StackName&UserId=UserId&Validity=Validity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a URL to start an AppStream 2."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a42497a7-f3f4-4c26-9ac0-0b84c03eebce"
            }
          ]
        }
      ]
    },
    {
      "name": "Stack",
      "item": [
        {
          "id": "c84c5102-a346-4c70-b9d0-8ab39aa4087b",
          "name": "DeleteStack",
          "request": {
            "url": "http://example.com/api/?Action=DeleteStack?Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "085566ca-3eb8-480c-8d54-8e043cb9a7e8"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "1d71c277-cd73-4814-b739-df0009269c14",
          "name": "DescribeImages",
          "request": {
            "url": "http://example.com/api/?Action=DescribeImages?Names=Names",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the images."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "226d1250-6752-40c3-88cd-ae7b804b054f"
            }
          ]
        }
      ]
    },
    {
      "name": "Sessions",
      "item": [
        {
          "id": "ee0e42b8-1c0a-4a9a-a0bd-be868d948379",
          "name": "DescribeSessions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSessions?FleetName=FleetName&Limit=Limit&NextToken=NextToken&StackName=StackName&UserId=UserId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the streaming sessions for a stack and a fleet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1fc9cecd-a267-4ced-8b28-00f091a53c26"
            }
          ]
        }
      ]
    },
    {
      "name": "Stacks",
      "item": [
        {
          "id": "e4e40671-c7f0-45e2-93f7-8208e64b9f48",
          "name": "DescribeStacks",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStacks?Names=Names&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "If stack names are not provided, this operation describes the specified stacks;\n            otherwise, all stacks in the account are described."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a99194ab-0009-46dc-8375-1bf0701cfd41"
            }
          ]
        }
      ]
    }
  ]
}