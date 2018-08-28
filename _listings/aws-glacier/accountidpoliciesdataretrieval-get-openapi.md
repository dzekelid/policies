---
swagger: "2.0"
x-collection-name: AWS Glacier
x-complete: 0
info:
  title: Amazon Glacier API Get  Data  Retrieval  Policy
  version: 1.0.0
  description: "DescriptionThis operation returns the current data retrieval policy
    for the account and region specified in the\n\t\t\t\tGET request. For more information
    about data retrieval policies, see\n\t\t\tAmazon Glacier Data Retrieval Policies.RequestsTo
    return the current data retrieval policy, send an HTTP GET request to the data
    retrieval\n\t\t\tpolicy URI as shown in the following syntax example."
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