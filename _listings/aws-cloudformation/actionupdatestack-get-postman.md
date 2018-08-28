{
  "info": {
    "name": "AWS CloudFormation API Update Stack",
    "_postman_id": "83f85b97-6a55-4c09-a313-01c7f82cb077",
    "description": "Updates a stack as specified in the template.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Stacks",
      "item": [
        {
          "id": "9f8782df-5f4a-481e-9258-b208e3518603",
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
              "id": "bd53b79d-be51-436b-a359-ab46f885df75"
            }
          ]
        },
        {
          "id": "09a19f26-28c7-4f21-ac71-571e444b4076",
          "name": "createStack",
          "request": {
            "url": "http://example.com/api/?Action=CreateStack?Capabilities.member.N=Capabilities.member.N&DisableRollback=DisableRollback&NotificationARNs.member.N=NotificationARNs.member.N&OnFailure=OnFailure&Parameters.member.N=Parameters.member.N&ResourceTypes.member.N=ResourceTypes.member.N&RoleARN=RoleARN&StackName=StackName&StackPolicyBody=StackPolicyBody&StackPolicyURL=StackPolicyURL&Tags.member.N=Tags.member.N&TemplateBody=TemplateBody&TemplateURL=TemplateURL&TimeoutInMinutes=TimeoutInMinutes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a stack as specified in the template."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3da2029c-6972-4641-9a19-181fd87d2161"
            }
          ]
        },
        {
          "id": "b8c69d0b-56b4-4b26-82f7-961398b5c40f",
          "name": "deleteStack",
          "request": {
            "url": "http://example.com/api/?Action=DeleteStack?RetainResources.member.N=RetainResources.member.N&RoleARN=RoleARN&StackName=StackName",
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
              "id": "77f7d6cf-820c-4fd6-8147-55e0ae5e208c"
            }
          ]
        },
        {
          "id": "23cff398-03ee-47e2-be4e-04d7f3e46d8b",
          "name": "describeStacks",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStacks?NextToken=NextToken&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the description for the specified stack; if no stack name was specified, then it returns the description for all the stacks created."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e5f307eb-425f-4f65-aac1-1f2441414bf8"
            }
          ]
        },
        {
          "id": "5b61a6ef-4d33-4558-b121-9a700168792f",
          "name": "listStacks",
          "request": {
            "url": "http://example.com/api/?Action=ListStacks?NextToken=NextToken&StackStatusFilter.member.N=StackStatusFilter.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the summary information for stacks whose status matches the specified StackStatusFilter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f57a339-8fb3-4e6e-9142-743c2f833cc2"
            }
          ]
        },
        {
          "id": "8db1d747-6b05-41df-bb45-65d925149179",
          "name": "updateStack",
          "request": {
            "url": "http://example.com/api/?Action=UpdateStack?Capabilities.member.N=Capabilities.member.N&NotificationARNs.member.N=NotificationARNs.member.N&Parameters.member.N=Parameters.member.N&ResourceTypes.member.N=ResourceTypes.member.N&RoleARN=RoleARN&StackName=StackName&StackPolicyBody=StackPolicyBody&StackPolicyDuringUpdateBody=StackPolicyDuringUpdateBody&StackPolicyDuringUpdateURL=StackPolicyDuringUpdateURL&StackPolicyURL=StackPolicyURL&Tags.member.N=Tags.member.N&TemplateBody=TemplateBody&TemplateURL=TemplateURL&UsePreviousTemplate=UsePreviousTemplate",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a stack as specified in the template."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc07555f-529b-46c0-9257-b5feb55b2149"
            }
          ]
        }
      ]
    },
    {
      "name": "Rollback",
      "item": [
        {
          "id": "83ba2bee-de2e-4003-b91a-a042d63cc61e",
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
              "id": "30ae20a7-23fe-4877-8dae-118d504e591d"
            }
          ]
        }
      ]
    },
    {
      "name": "Change Sets",
      "item": [
        {
          "id": "f628d5e6-8ddc-4a73-9810-13872d8b227c",
          "name": "createChangeSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateChangeSet?Capabilities.member.N=Capabilities.member.N&ChangeSetName=ChangeSetName&ChangeSetType=ChangeSetType&ClientToken=ClientToken&Description=Description&NotificationARNs.member.N=NotificationARNs.member.N&Parameters.member.N=Parameters.member.N&ResourceTypes.member.N=ResourceTypes.member.N&RoleARN=RoleARN&StackName=StackName&Tags.member.N=Tags.member.N&TemplateBody=TemplateBody&TemplateURL=TemplateURL&UsePreviousTemplate=UsePreviousTemplate",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a list of changes for a stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "064be3fc-f018-4e0d-a8fe-2b88a392cca7"
            }
          ]
        },
        {
          "id": "315d64c8-94ab-44dd-8cbf-e94d4929978a",
          "name": "deleteChangeSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteChangeSet?ChangeSetName=ChangeSetName&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified change set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d8b0af84-b452-4940-a9ae-1a95ed07a35b"
            }
          ]
        },
        {
          "id": "503728a4-d554-40ce-8e7e-9182ffc4f855",
          "name": "describeChangeSet",
          "request": {
            "url": "http://example.com/api/?Action=DescribeChangeSet?ChangeSetName=ChangeSetName&NextToken=NextToken&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the inputs for the change set and a list of changes that AWS CloudFormation will make if you execute the change set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9dda342-4293-4878-a2ae-7271da6b0405"
            }
          ]
        },
        {
          "id": "552ef31f-f2fc-46c7-bff1-2ccadcaf6f0c",
          "name": "executeChangeSet",
          "request": {
            "url": "http://example.com/api/?Action=ExecuteChangeSet?ChangeSetName=ChangeSetName&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a stack using the input information that was provided when the specified change set was created."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e17913d4-7177-41c3-8993-ed74a25e19a6"
            }
          ]
        },
        {
          "id": "a8fce796-ddab-495f-b706-8a632972e073",
          "name": "listChangeSets",
          "request": {
            "url": "http://example.com/api/?Action=ListChangeSets?NextToken=NextToken&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the ID and status of each active change set for a stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "283c1d51-a1e9-43e4-b5e7-9e3f9cd0a4ba"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Limits",
      "item": [
        {
          "id": "bff2ee17-059f-4b2b-9e3e-b899909f31dd",
          "name": "describeAccountLimits",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAccountLimits?NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves your account's AWS CloudFormation limits, such as the maximum number of stacks that you can create in your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "004aa8e0-460c-4f78-a52f-af9b096a1311"
            }
          ]
        }
      ]
    },
    {
      "name": "Stack Events",
      "item": [
        {
          "id": "969fc433-89c4-4530-8334-0d3f130baf04",
          "name": "describeStackEvents",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStackEvents?NextToken=NextToken&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all stack related events for a specified stack in reverse chronological order."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9966b2bd-5559-4caf-987a-40c61204165b"
            }
          ]
        }
      ]
    },
    {
      "name": "Stack Resources",
      "item": [
        {
          "id": "1bae853f-64bb-4134-a3cc-bd5299db913b",
          "name": "describeStackResource",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStackResource?LogicalResourceId=LogicalResourceId&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a description of the specified resource in the specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8f98f576-6be6-4db8-ac18-3ad6c7f1388c"
            }
          ]
        },
        {
          "id": "cc53ff0b-216d-463c-8f61-5034c617e1fa",
          "name": "describeStackResources",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStackResources?LogicalResourceId=LogicalResourceId&PhysicalResourceId=PhysicalResourceId&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns AWS resource descriptions for running and deleted stacks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60d6397a-8115-463f-91bf-d299d272e505"
            }
          ]
        },
        {
          "id": "28c9bba3-ad81-4e78-abd9-eb4a329a4a12",
          "name": "listStackResources",
          "request": {
            "url": "http://example.com/api/?Action=ListStackResources?NextToken=NextToken&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns descriptions of all resources of the specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da290526-a752-49e0-bf2c-bc76ff069a4b"
            }
          ]
        }
      ]
    },
    {
      "name": "Template Cost",
      "item": [
        {
          "id": "77bba3e1-4fd4-479a-a252-fea016e387fb",
          "name": "estimateTemplateCost",
          "request": {
            "url": "http://example.com/api/?Action=EstimateTemplateCost?Parameters.member.N=Parameters.member.N&TemplateBody=TemplateBody&TemplateURL=TemplateURL",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the estimated monthly cost of a template."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6641f3c1-03da-42de-a5ee-7187f42b6f0b"
            }
          ]
        }
      ]
    },
    {
      "name": "Stack Policies",
      "item": [
        {
          "id": "0abea4a6-6ef6-4fdf-8417-2f3eb3d4ffbc",
          "name": "getStackPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetStackPolicy?StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the stack policy for a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5cf0b45a-92ce-429c-9982-858ebeda1d6c"
            }
          ]
        },
        {
          "id": "4a17bcd2-e4bb-45d7-a9bc-fa45873846e8",
          "name": "setStackPolicy",
          "request": {
            "url": "http://example.com/api/?Action=SetStackPolicy?StackName=StackName&StackPolicyBody=StackPolicyBody&StackPolicyURL=StackPolicyURL",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets a stack policy for a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5be45bae-32e7-4eb2-8a78-ad11178c079e"
            }
          ]
        }
      ]
    },
    {
      "name": "Templates",
      "item": [
        {
          "id": "a66b4044-827d-4b30-971a-65691352597b",
          "name": "getTemplate",
          "request": {
            "url": "http://example.com/api/?Action=GetTemplate?ChangeSetName=ChangeSetName&StackName=StackName&TemplateStage=TemplateStage",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the template body for a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b961a85b-eac2-465c-a96c-0581c110f651"
            }
          ]
        },
        {
          "id": "1c19fac1-ac50-4b88-85ae-7e8287a8dc5f",
          "name": "getTemplateSummary",
          "request": {
            "url": "http://example.com/api/?Action=GetTemplateSummary?StackName=StackName&TemplateBody=TemplateBody&TemplateURL=TemplateURL",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about a new or existing template."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea8913b5-793c-4d9b-8599-c55b106f6dd6"
            }
          ]
        }
      ]
    },
    {
      "name": "Exports",
      "item": [
        {
          "id": "a95b70f6-ad66-4432-a0a2-bebdb329d783",
          "name": "listExports",
          "request": {
            "url": "http://example.com/api/?Action=ListExports?NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all exported output values in the account and region in which you call this action."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d3ffbcc9-d7d8-4228-b78a-3f1d610c4f4a"
            }
          ]
        }
      ]
    },
    {
      "name": "Imports",
      "item": [
        {
          "id": "66932f3b-6394-4f21-8ade-e2b679ddedb3",
          "name": "listImports",
          "request": {
            "url": "http://example.com/api/?Action=ListImports?ExportName=ExportName&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all stacks that are importing an exported output value."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0705a1f0-1fb8-4002-9abe-6f587d495158"
            }
          ]
        }
      ]
    },
    {
      "name": "Signal Resources",
      "item": [
        {
          "id": "d58cad19-1863-465f-8cfe-f16641e1bdbb",
          "name": "signalResource",
          "request": {
            "url": "http://example.com/api/?Action=SignalResource?LogicalResourceId=LogicalResourceId&StackName=StackName&Status=Status&UniqueId=UniqueId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sends a signal to the specified resource with a success or failure status."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ed65392-85c0-46d1-a6be-872f61e897ff"
            }
          ]
        }
      ]
    }
  ]
}