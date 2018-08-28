---
swagger: "2.0"
x-collection-name: AWS Internet of Things
x-complete: 0
info:
  title: AWS Internet of Things API List Policy Principals
  version: 1.0.0
  description: Lists the principals associated with the specified policy.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreatePolicy:
    get:
      summary: Create Policy
      description: Creates an AWS IoT policy.
      operationId: createPolicy
      x-api-path-slug: actioncreatepolicy-get
      parameters:
      - in: query
        name: policyDocument
        description: The JSON document that describes the policy
        type: string
      - in: query
        name: policyName
        description: The policy name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
  /?Action=CreatePolicyVersion:
    get:
      summary: Create Policy Version
      description: Creates a new version of the specified AWS IoT policy.
      operationId: createPolicyVersion
      x-api-path-slug: actioncreatepolicyversion-get
      parameters:
      - in: query
        name: policyDocument
        description: The JSON document that describes the policy
        type: string
      - in: query
        name: policyName
        description: The policy name
        type: string
      - in: query
        name: setAsDefault
        description: Specifies whether the policy version is set as the default
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
  /?Action=DeletePolicy:
    get:
      summary: Delete Policy
      description: Deletes the specified policy.
      operationId: deletePolicy
      x-api-path-slug: actiondeletepolicy-get
      parameters:
      - in: query
        name: policyName
        description: The name of the policy to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
  /?Action=DeletePolicyVersion:
    get:
      summary: Delete Policy Version
      description: Deletes the specified version of the specified policy.
      operationId: deletePolicyVersion
      x-api-path-slug: actiondeletepolicyversion-get
      parameters:
      - in: query
        name: policyName
        description: The name of the policy
        type: string
      - in: query
        name: policyVersionId
        description: The policy version ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
  /?Action=GetPolicy:
    get:
      summary: Get Policy
      description: Gets information about the specified policy with the policy document
        of the default version.
      operationId: getPolicy
      x-api-path-slug: actiongetpolicy-get
      parameters:
      - in: query
        name: policyName
        description: The name of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
  /?Action=GetPolicyVersion:
    get:
      summary: Get Policy Version
      description: Gets information about the specified policy version.
      operationId: getPolicyVersion
      x-api-path-slug: actiongetpolicyversion-get
      parameters:
      - in: query
        name: policyName
        description: The name of the policy
        type: string
      - in: query
        name: policyVersionId
        description: The policy version ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
  /?Action=ListPolicies:
    get:
      summary: List Policies
      description: Lists your policies.
      operationId: listPolicies
      x-api-path-slug: actionlistpolicies-get
      parameters:
      - in: query
        name: ascendingOrder
        description: Specifies the order for results
        type: string
      - in: query
        name: marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: pageSize
        description: The result page size
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
  /?Action=SetDefaultPolicyVersion:
    get:
      summary: Set Default Policy Version
      description: Sets the specified version of the specified policy as the policy's
        default (operative) version.
      operationId: setDefaultPolicyVersion
      x-api-path-slug: actionsetdefaultpolicyversion-get
      parameters:
      - in: query
        name: policyName
        description: The policy name
        type: string
      - in: query
        name: policyVersionId
        description: The policy version ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
  /?Action=ListPrincipalPolicies:
    get:
      summary: List Principal Policies
      description: Lists the policies attached to the specified principal.
      operationId: listPrincipalPolicies
      x-api-path-slug: actionlistprincipalpolicies-get
      parameters:
      - in: query
        name: ascendingOrder
        description: Specifies the order for results
        type: string
      - in: query
        name: marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: pageSize
        description: The result page size
        type: string
      - in: query
        name: principal
        description: The principal
        type: string
      responses:
        200:
          description: OK
      tags:
      - Principal Policies
  /?Action=AttachPrincipalPolicy:
    get:
      summary: Attach Principal Policy
      description: Attaches the specified policy to the specified principal (certificate
        or other credential).
      operationId: attachPrincipalPolicy
      x-api-path-slug: actionattachprincipalpolicy-get
      parameters:
      - in: query
        name: policyName
        description: The policy name
        type: string
      - in: query
        name: principal
        description: The principal, which can be a certificate ARN (as returned from
          the CreateCertificate operation) or an Amazon Cognito ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Principal Policies
  /?Action=DetachPrincipalPolicy:
    get:
      summary: Detach Principal Policy
      description: Removes the specified policy from the specified certificate.
      operationId: detachPrincipalPolicy
      x-api-path-slug: actiondetachprincipalpolicy-get
      parameters:
      - in: query
        name: policyName
        description: The name of the policy to detach
        type: string
      - in: query
        name: principal
        description: The principal
        type: string
      responses:
        200:
          description: OK
      tags:
      - Principal Policies
  /?Action=ListPolicyPrincipals:
    get:
      summary: List Policy Principals
      description: Lists the principals associated with the specified policy.
      operationId: listPolicyPrincipals
      x-api-path-slug: actionlistpolicyprincipals-get
      parameters:
      - in: query
        name: ascendingOrder
        description: Specifies the order for results
        type: string
      - in: query
        name: marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: pageSize
        description: The result page size
        type: string
      - in: query
        name: policyName
        description: The policy name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policy Principals
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