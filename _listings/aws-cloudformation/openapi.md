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
  /?Action=GetStackPolicy:
    get:
      summary: Get Stack Policy
      description: Returns the stack policy for a specified stack.
      operationId: getStackPolicy
      x-api-path-slug: actiongetstackpolicy-get
      parameters:
      - in: query
        name: StackName
        description: The name or unique stack ID that is associated with the stack
          whose policy you want to get
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stack Policies
  /?Action=SetStackPolicy:
    get:
      summary: Set Stack Policy
      description: Sets a stack policy for a specified stack.
      operationId: setStackPolicy
      x-api-path-slug: actionsetstackpolicy-get
      parameters:
      - in: query
        name: StackName
        description: The name or unique stack ID that you want to associate a policy
          with
        type: string
      - in: query
        name: StackPolicyBody
        description: Structure containing the stack policy body
        type: string
      - in: query
        name: StackPolicyURL
        description: Location of a file containing the stack policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stack Policies