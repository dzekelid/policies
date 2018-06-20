---
swagger: "2.0"
x-collection-name: AWS Key Management Service
x-complete: 0
info:
  title: AWS Key Management Service API Get Key Policy
  version: 1.0.0
  description: Retrieves a policy attached to the specified key.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetKeyPolicy:
    get:
      summary: Get Key Policy
      description: Retrieves a policy attached to the specified key.
      operationId: getKeyPolicy
      x-api-path-slug: actiongetkeypolicy-get
      parameters:
      - in: query
        name: KeyId
        description: A unique identifier for the customer master key
        type: string
      - in: query
        name: PolicyName
        description: String that contains the name of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Key Policies
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