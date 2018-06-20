---
swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 1
info:
  title: AWS OpsWorks API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeStacks:
    get:
      summary: Describe Stacks
      description: Requests a description of one or more stacks.
      operationId: describeStacks
      x-api-path-slug: actiondescribestacks-get
      parameters:
      - in: query
        name: StackIds
        description: An array of stack IDs that specify the stacks to be described
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Stacks
---