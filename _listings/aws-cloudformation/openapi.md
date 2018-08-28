swagger: "2.0"
x-collection-name: AWS CloudFormation
x-complete: 1
info:
  title: AWS CloudFormation API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CancelUpdateStack:
    get:
      summary: Cancel Update Stack
      description: Cancels an update on the specified stack.
      operationId: cancelUpdateStack
      x-api-path-slug: actioncancelupdatestack-get
      parameters:
      - in: query
        name: StackName
        description: The name or the unique stack ID that is associated with the stack
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stacks
  /?Action=CreateStack:
    get:
      summary: Create Stack
      description: Creates a stack as specified in the template.
      operationId: createStack
      x-api-path-slug: actioncreatestack-get
      parameters:
      - in: query
        name: Capabilities.member.N
        description: A list of values that you must specify before AWS CloudFormation
          can create certain stacks
        type: string
      - in: query
        name: DisableRollback
        description: Set to true to disable rollback of the stack if stack creation
          failed
        type: string
      - in: query
        name: NotificationARNs.member.N
        description: The Simple Notification Service (SNS) topic ARNs to publish stack
          related events
        type: string
      - in: query
        name: OnFailure
        description: Determines what action will be taken if stack creation fails
        type: string
      - in: query
        name: Parameters.member.N
        description: A list of Parameter structures that specify input parameters
          for the stack
        type: string
      - in: query
        name: ResourceTypes.member.N
        description: The template resource types that you have permissions to work
          with for this create stack action, such as AWS::EC2::Instance, AWS::EC2::*,
          or Custom::MyCustomInstance
        type: string
      - in: query
        name: RoleARN
        description: The Amazon Resource Name (ARN) of an AWS Identity and Access
          Management (IAM) role that AWS CloudFormation         assumes to create
          the stack
        type: string
      - in: query
        name: StackName
        description: The name that is associated with the stack
        type: string
      - in: query
        name: StackPolicyBody
        description: Structure containing the stack policy body
        type: string
      - in: query
        name: StackPolicyURL
        description: Location of a file containing the stack policy
        type: string
      - in: query
        name: Tags.member.N
        description: Key-value pairs to associate with this stack
        type: string
      - in: query
        name: TemplateBody
        description: Structure containing the template body with a minimum length
          of 1 byte and a maximum length of 51,200 bytes
        type: string
      - in: query
        name: TemplateURL
        description: Location of file containing the template body
        type: string
      - in: query
        name: TimeoutInMinutes
        description: The amount of time that can pass before the stack status becomes
          CREATE_FAILED; if DisableRollback         is not set or is set to false,
          the stack will be rolled back
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stacks
  /?Action=DeleteStack:
    get:
      summary: Delete Stack
      description: Deletes a specified stack.
      operationId: deleteStack
      x-api-path-slug: actiondeletestack-get
      parameters:
      - in: query
        name: RetainResources.member.N
        description: For stacks in the DELETE_FAILED state, a list of resource logical
          IDs that are associated with          the resources you want to retain
        type: string
      - in: query
        name: RoleARN
        description: The Amazon Resource Name (ARN) of an AWS Identity and Access
          Management (IAM) role that AWS CloudFormation         assumes to delete
          the stack
        type: string
      - in: query
        name: StackName
        description: The name or the unique stack ID that is associated with the stack
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stacks
  /?Action=DescribeStacks:
    get:
      summary: Describe Stacks
      description: Returns the description for the specified stack; if no stack name
        was specified, then it returns the description for all the stacks created.
      operationId: describeStacks
      x-api-path-slug: actiondescribestacks-get
      parameters:
      - in: query
        name: NextToken
        description: A string that identifies the next page of stacks that you want
          to retrieve
        type: string
      - in: query
        name: StackName
        description: 'The name or the unique stack ID that is associated with the
          stack, which are not always interchangeable:'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stacks
  /?Action=ListStacks:
    get:
      summary: List Stacks
      description: Returns the summary information for stacks whose status matches
        the specified StackStatusFilter.
      operationId: listStacks
      x-api-path-slug: actionliststacks-get
      parameters:
      - in: query
        name: NextToken
        description: A string that identifies the next page of stacks that you want
          to retrieve
        type: string
      - in: query
        name: StackStatusFilter.member.N
        description: Stack status to use as a filter
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stacks
  /?Action=UpdateStack:
    get:
      summary: Update Stack
      description: Updates a stack as specified in the template.
      operationId: updateStack
      x-api-path-slug: actionupdatestack-get
      parameters:
      - in: query
        name: Capabilities.member.N
        description: A list of values that you must specify before AWS CloudFormation
          can update certain stacks
        type: string
      - in: query
        name: NotificationARNs.member.N
        description: Amazon Simple Notification Service topic Amazon Resource Names
          (ARNs) that AWS CloudFormation associates with the stack
        type: string
      - in: query
        name: Parameters.member.N
        description: A list of Parameter structures that specify input parameters
          for the stack
        type: string
      - in: query
        name: ResourceTypes.member.N
        description: The template resource types that you have permissions to work
          with for this update stack action, such as AWS::EC2::Instance, AWS::EC2::*,
          or Custom::MyCustomInstance
        type: string
      - in: query
        name: RoleARN
        description: The Amazon Resource Name (ARN) of an AWS Identity and Access
          Management (IAM) role that AWS CloudFormation         assumes to update
          the stack
        type: string
      - in: query
        name: StackName
        description: The name or unique stack ID of the stack to update
        type: string
      - in: query
        name: StackPolicyBody
        description: Structure containing a new stack policy body
        type: string
      - in: query
        name: StackPolicyDuringUpdateBody
        description: Structure containing the temporary overriding stack policy body
        type: string
      - in: query
        name: StackPolicyDuringUpdateURL
        description: Location of a file containing the temporary overriding stack
          policy
        type: string
      - in: query
        name: StackPolicyURL
        description: Location of a file containing the updated stack policy
        type: string
      - in: query
        name: Tags.member.N
        description: Key-value pairs to associate with this stack
        type: string
      - in: query
        name: TemplateBody
        description: Structure containing the template body with a minimum length
          of 1 byte and a maximum length of 51,200 bytes
        type: string
      - in: query
        name: TemplateURL
        description: Location of file containing the template body
        type: string
      - in: query
        name: UsePreviousTemplate
        description: Reuse the existing template that is associated with the stack
          that you are updating
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stacks