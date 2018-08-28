---
swagger: "2.0"
x-collection-name: AWS CloudFormation
x-complete: 0
info:
  title: AWS CloudFormation API Get Stack Policy
  version: 1.0.0
  description: Returns the stack policy for a specified stack.
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