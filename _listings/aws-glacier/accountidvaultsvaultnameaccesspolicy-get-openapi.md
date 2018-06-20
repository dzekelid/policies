---
swagger: "2.0"
x-collection-name: AWS Glacier
x-complete: 0
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
  /{AccountId}/policies/data-retrieval:
    get:
      summary: Get  Data  Retrieval  Policy
      description: "DescriptionThis operation returns the current data retrieval policy
        for the account and region specified in the\n\t\t\t\tGET request. For more
        information about data retrieval policies, see\n\t\t\tAmazon Glacier Data
        Retrieval Policies.RequestsTo return the current data retrieval policy, send
        an HTTP GET request to the data retrieval\n\t\t\tpolicy URI as shown in the
        following syntax example."
      operationId: Get Data Retrieval Policy (GET policy)
      x-api-path-slug: accountidpoliciesdataretrieval-get
      parameters:
      - in: query
        name: BytesPerHour
        description: The maximum number of bytes that can be retrieved in an hour
        type: string
      - in: query
        name: Rules
        description: The policy rule
        type: string
      - in: query
        name: Strategy
        description: The type of data retrieval policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Data  Retrieval  Policies
  /{AccountId}/vaults/{vaultName}/access-policy:
    delete:
      summary: Delete  Vault  Access  Policy
      description: "DescriptionThis operation deletes the access policy associated
        with the specified vault. The\n\t\t\toperation is eventually consistent&#8212;that
        is, it might take some time for Amazon Glacier to\n\t\t\tcompletely remove
        the access policy, and you might still see the effect of the policy\n\t\t\tfor
        a short time after you send the delete request. This operation is idempotent.
        You can invoke delete multiple times, even if there is\n\t\t\tno policy associated
        with the vault. For more information about vault access policies,\n\t\t\tsee
        Amazon Glacier Access Control with Vault Access Policies.RequestsTo delete
        the current vault access policy, send an HTTP DELETE request to\n\t\t\tthe
        URI of the vault's access-policy subresource."
      operationId: "Delete Vault Access Policy (DELETE\n\t\taccess-policy)"
      x-api-path-slug: accountidvaultsvaultnameaccesspolicy-delete
      responses:
        200:
          description: OK
      tags:
      - Vault Access Policies
    get:
      summary: Get  Vault  Access  Policy
      description: "DescriptionThis operation retrieves the access-policy subresource
        set on the\n\t\t\tvault&#8212;for more information on setting this subresource,
        see Set Vault Access Policy (PUT access-policy). If\n\t\t\tthere is no access
        policy set on the vault, the operation returns a 404 Not\n\t\t\t\tfound error.
        For more information about vault access policies, see Amazon Glacier Access
        Control with Vault Access Policies.RequestsTo return the current vault access
        policy, send an HTTP GET request to\n\t\t\tthe URI of the vault's access-policy
        subresource."
      operationId: Get Vault Access Policy (GET access-policy)
      x-api-path-slug: accountidvaultsvaultnameaccesspolicy-get
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
      - Vault Access Policies
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