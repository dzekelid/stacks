---
swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 0
info:
  title: AWS OpsWorks API Register Instance
  version: 1.0.0
  description: Registers instances that were created outside of AWS OpsWorks Stacks
    with a specified stack.
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
  /?Action=DescribeAgentVersions:
    get:
      summary: Describe Agent Versions
      description: Describes the available AWS OpsWorks Stacks agent versions.
      operationId: describeAgentVersions
      x-api-path-slug: actiondescribeagentversions-get
      parameters:
      - in: query
        name: ConfigurationManager
        description: The configuration manager
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Agent
      - Versions
  /?Action=DescribeServiceErrors:
    get:
      summary: Describe Service Errors
      description: Describes AWS OpsWorks Stacks service errors.
      operationId: describeServiceErrors
      x-api-path-slug: actiondescribeserviceerrors-get
      parameters:
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      - in: query
        name: ServiceErrorIds
        description: An array of service error IDs
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Service
      - Errors
  /?Action=RegisterInstance:
    get:
      summary: Register Instance
      description: Registers instances that were created outside of AWS OpsWorks Stacks
        with a specified stack.
      operationId: registerInstance
      x-api-path-slug: actionregisterinstance-get
      parameters:
      - in: query
        name: Hostname
        description: The instances hostname
        type: string
      - in: query
        name: InstanceIdentity
        description: An InstanceIdentity object that contains the instances identity
        type: string
      - in: query
        name: PrivateIp
        description: The instances private IP address
        type: string
      - in: query
        name: PublicIp
        description: The instances public IP address
        type: string
      - in: query
        name: RsaPublicKey
        description: The instances public RSA key
        type: string
      - in: query
        name: RsaPublicKeyFingerprint
        description: The instances public RSA key fingerprint
        type: string
      - in: query
        name: StackId
        description: The ID of the stack that the instance is to be registered with
        type: string
      responses:
        200:
          description: OK
      tags:
      - Register
      - Instance
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---