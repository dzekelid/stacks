---
name: AWS AppStream 2.0
x-slug: aws-appstream-2-0
description: Amazon AppStream 2.0 is a fully managed, secure application streaming
  service that allows you to stream desktop applications from AWS to any device running
  a web browser, without rewriting them. Amazon AppStream 2.0 provides users instant-on
  access to the applications they need, and a responsive, fluid user experience on
  the device of their choice.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Stacks
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-appstream-2-0/apis.md
specificationVersion: "0.14"
apis:
- name: AWS AppStream 2.0 API Describe Stacks
  x-api-slug: aws-appstream-2-0-api
  description: |-
    If stack names are not provided, this operation describes the specified stacks;
                otherwise, all stacks in the account are described.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: ://///?Action=DescribeStacks
  tags: Stacks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-appstream-2-0/actiondescribestacks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-appstream-2-0/actiondescribestacks-get-openapi.md
- name: AWS AppStream 2.0 API
  x-api-slug: aws-appstream-2-0-api
  description: Amazon AppStream 2.0 is a fully managed, secure application streaming
    service that allows you to stream desktop applications from AWS to any device
    running a web browser, without rewriting them. Amazon AppStream 2.0 provides users
    instant-on access to the applications they need, and a responsive, fluid user
    experience on the device of their choice.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/appstream2_try_it_now_2_big.png
  humanURL: https://aws.amazon.com/appstream2/
  baseURL: :///
  tags: Stacks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stacks/master/_listings/aws-appstream-2-0/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/appstream2/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/appstream2/faqs/
- type: x-forum
  url: https://aws.amazon.com/appstream2/resources/#forum
- type: x-getting-started
  url: https://aws.amazon.com/appstream2/resources/#getting_starte
- type: x-pricing
  url: https://aws.amazon.com/appstream2/pricing/
- type: x-website
  url: https://aws.amazon.com/appstream2/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---