---
name: AWS OpsWorks
x-slug: aws-opsworks
description: AWS OpsWorks is a configuration management service that uses Chef, an
  automation platform that treats server configurations as code. OpsWorks uses Chef
  to automate how servers are configured, deployed, and managed across your Amazon
  Elastic Compute Cloud (Amazon EC2) instances or on-premises compute environments.
  OpsWorks has two offerings, AWS Opsworks for Chef Automate, and AWS OpsWorks Stacks.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Stacks
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-opsworks/apis.md
specificationVersion: "0.14"
apis:
- name: AWS OpsWorks API Describe Stacks
  x-api-slug: aws-opsworks-api
  description: Requests a description of one or more stacks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeStacks
  tags: Describe,Stacks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-opsworks/actiondescribestacks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-opsworks/actiondescribestacks-get-openapi.md
- name: AWS OpsWorks API
  x-api-slug: aws-opsworks-api
  description: AWS OpsWorks is a configuration management service that uses Chef,
    an automation platform that treats server configurations as code. OpsWorks uses
    Chef to automate how servers are configured, deployed, and managed across your
    Amazon Elastic Compute Cloud (Amazon EC2) instances or on-premises compute environments.
    OpsWorks has two offerings, AWS Opsworks for Chef Automate, and AWS OpsWorks Stacks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: :///
  tags: Stacks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-opsworks/openapi.md
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html
- type: x-documentation
  url: http://docs.aws.amazon.com/opsworks/latest/APIReference/Welcome.html
- type: x-website
  url: https://aws.amazon.com/opsworks/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---