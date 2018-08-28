swagger: "2.0"
x-collection-name: AWS Key Management Service
x-complete: 1
info:
  title: AWS Key Management Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListKeyPolicies:
    get:
      summary: List Key Policies
      description: Retrieves a list of policies attached to a key.
      operationId: listKeyPolicies
      x-api-path-slug: actionlistkeypolicies-get
      parameters:
      - in: query
        name: KeyId
        description: A unique identifier for the customer master key (CMK)
        type: string
      - in: query
        name: Limit
        description: When paginating results, specify the maximum number of items
          to return in the response
        type: string
      - in: query
        name: Marker
        description: Use this parameter only when paginating results and only in a
          subsequent request after      you receive a response with truncated results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
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
  /?Action=PutKeyPolicy:
    get:
      summary: Put Key Policy
      description: Attaches a key policy to the specified customer master key (CMK).
      operationId: putKeyPolicy
      x-api-path-slug: actionputkeypolicy-get
      parameters:
      - in: query
        name: BypassPolicyLockoutSafetyCheck
        description: A flag to indicate whether to bypass the key policy lockout safety
          check
        type: string
      - in: query
        name: KeyId
        description: A unique identifier for the CMK
        type: string
      - in: query
        name: Policy
        description: The key policy to attach to the CMK
        type: string
      - in: query
        name: PolicyName
        description: The name of the key policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Keys