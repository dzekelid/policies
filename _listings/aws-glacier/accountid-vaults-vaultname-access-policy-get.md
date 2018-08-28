---
swagger: "2.0"
info:
  title: Amazon Glacier API Get  Vault  Access  Policy
  version: 1.0.0
  description: "DescriptionThis operation retrieves the access-policy subresource
    set on the\n\t\t\tvault&#8212;for more information on setting this subresource,
    see Set Vault Access Policy (PUT access-policy). If\n\t\t\tthere is no access
    policy set on the vault, the operation returns a 404 Not\n\t\t\t\tfound error.
    For more information about vault access policies, see Amazon Glacier Access Control
    with Vault Access Policies.RequestsTo return the current vault access policy,
    send an HTTP GET request to\n\t\t\tthe URI of the vault's access-policy subresource."
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{AccountId}/vaults/{vaultName}/access-policy:
    get:
      summary: Get  Vault  Access  Policy
      description: "DescriptionThis operation retrieves the access-policy subresource
        set on the\n\t\t\tvault&#8212;for more information on setting this subresource,
        see Set Vault Access Policy (PUT access-policy)"
      operationId: Get Vault Access Policy (GET access-policy)
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