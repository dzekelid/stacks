---
name: AWS CloudFormation
x-slug: aws-cloudformation
description: AWS CloudFormation gives developers and systems administrators an easy
  way to create and manage a collection of related AWS resources, provisioning and
  updating them in an orderly and predictable fashion.You can use AWS CloudFormations?sample
  templates?or create your own templates to describe the AWS resources, and any associated
  dependencies or runtime parameters, required to run your application. You do not
  need to figure out the order for provisioning AWS services or the subtleties of
  making those dependencies work. CloudFormation takes care of this for you. After
  the AWS resources are deployed, you can modify and update them in a controlled and
  predictable way, in effect applying version control to your AWS infrastructure the
  same way you do with your software. You can also visualize your templates as diagrams
  and edit them using a drag-and-drop interface with the?AWS CloudFormation Designer.You
  can deploy and update a template and its associated collection of resources (called
  a stack) by using the AWS Management Console, AWS Command Line Interface, or APIs.
  CloudFormation is available at no additional charge, and you pay only for the AWS
  resources needed to run your applications.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSCloudFormation.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Stacks
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-cloudformation/apis.md
specificationVersion: "0.14"
apis:
- name: AWS CloudFormation API Cancel Update Stack
  x-api-slug: aws-cloudformation-api
  description: Cancels an update on the specified stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSCloudFormation.png
  humanURL: https://aws.amazon.com/cloudformation/
  baseURL: ://///?Action=CancelUpdateStack
  tags: Stacks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-cloudformation/actioncancelupdatestack-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-cloudformation/actioncancelupdatestack-get-openapi.md
- name: AWS CloudFormation API Create Stack
  x-api-slug: aws-cloudformation-api
  description: Creates a stack as specified in the template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSCloudFormation.png
  humanURL: https://aws.amazon.com/cloudformation/
  baseURL: ://///?Action=CreateStack
  tags: Stacks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-cloudformation/actioncreatestack-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-cloudformation/actioncreatestack-get-openapi.md
- name: AWS CloudFormation API Delete Stack
  x-api-slug: aws-cloudformation-api
  description: Deletes a specified stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSCloudFormation.png
  humanURL: https://aws.amazon.com/cloudformation/
  baseURL: ://///?Action=DeleteStack
  tags: Stacks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-cloudformation/actiondeletestack-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-cloudformation/actiondeletestack-get-openapi.md
- name: AWS CloudFormation API Describe Stacks
  x-api-slug: aws-cloudformation-api
  description: Returns the description for the specified stack; if no stack name was
    specified, then it returns the description for all the stacks created.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSCloudFormation.png
  humanURL: https://aws.amazon.com/cloudformation/
  baseURL: ://///?Action=DescribeStacks
  tags: Stacks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-cloudformation/actiondescribestacks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-cloudformation/actiondescribestacks-get-openapi.md
- name: AWS CloudFormation API List Stacks
  x-api-slug: aws-cloudformation-api
  description: Returns the summary information for stacks whose status matches the
    specified StackStatusFilter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSCloudFormation.png
  humanURL: https://aws.amazon.com/cloudformation/
  baseURL: ://///?Action=ListStacks
  tags: Stacks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-cloudformation/actionliststacks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-cloudformation/actionliststacks-get-openapi.md
- name: AWS CloudFormation API Update Stack
  x-api-slug: aws-cloudformation-api
  description: Updates a stack as specified in the template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSCloudFormation.png
  humanURL: https://aws.amazon.com/cloudformation/
  baseURL: ://///?Action=UpdateStack
  tags: Stacks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-cloudformation/actionupdatestack-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-cloudformation/actionupdatestack-get-openapi.md
- name: AWS CloudFormation API
  x-api-slug: aws-cloudformation-api
  description: AWS CloudFormation gives developers and systems administrators an easy
    way to create and manage a collection of related AWS resources, provisioning and
    updating them in an orderly and predictable fashion.You can use AWS CloudFormations?sample
    templates?or create your own templates to describe the AWS resources, and any
    associated dependencies or runtime parameters, required to run your application.
    You do not need to figure out the order for provisioning AWS services or the subtleties
    of making those dependencies work. CloudFormation takes care of this for you.
    After the AWS resources are deployed, you can modify and update them in a controlled
    and predictable way, in effect applying version control to your AWS infrastructure
    the same way you do with your software. You can also visualize your templates
    as diagrams and edit them using a drag-and-drop interface with the?AWS CloudFormation
    Designer.You can deploy and update a template and its associated collection of
    resources (called a stack) by using the AWS Management Console, AWS Command Line
    Interface, or APIs. CloudFormation is available at no additional charge, and you
    pay only for the AWS resources needed to run your applications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSCloudFormation.png
  humanURL: https://aws.amazon.com/cloudformation/
  baseURL: :///
  tags: Stacks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-cloudformation/openapi.md
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/cloudformation/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/cloudformation/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/cloudformation/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/cloudformation/pricing/
- type: x-sdk
  url: https://aws.amazon.com/cloudformation/aws-cloudformation-templates/
- type: x-website
  url: https://aws.amazon.com/cloudformation/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---