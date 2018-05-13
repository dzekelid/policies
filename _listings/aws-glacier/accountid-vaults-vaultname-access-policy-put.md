---
swagger: "2.0"
info:
  title: Amazon Glacier API Set  Vault  Access  Policy
  version: 1.0.0
  description: "DescriptionThis operation configures an access policy for a vault
    and will overwrite an existing\n\t\t\tpolicy. To configure a vault access policy,
    send a PUT request to the\n\t\t\t\taccess-policy subresource of the vault. You
    can set one access policy per vault\n\t\t\tand the policy can be up to 20 KB in
    size. For more information about vault access\n\t\t\tpolicies, see Amazon Glacier
    Access Control with Vault Access Policies. Requests"
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{AccountId}/vaults/{vaultName}/access-policy:
    put:
      summary: Set  Vault  Access  Policy
      description: "DescriptionThis operation configures an access policy for a vault
        and will overwrite an existing\n\t\t\tpolicy"
      operationId: Set Vault Access Policy (PUT access-policy)
      parameters:
      - in: query
        name: Policy
        description: The vault access policy as a JSON string, which uses \ as an
          escape character
        type: string
      responses:
        200:
          description: OK
      tags:
      - vault access policies
definitions: []
x-collection-name: AWS Glacier
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