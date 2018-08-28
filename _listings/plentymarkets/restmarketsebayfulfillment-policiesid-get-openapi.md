---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Get fulfillment policy
  description: Get fulfillment policy for given ID.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/markets/ebay/fulfillment_policies/{id}:
    get:
      summary: Get fulfillment policy
      description: Get fulfillment policy for given ID.
      operationId: getRestMarketsEbayFulfillmentPolicies
      x-api-path-slug: restmarketsebayfulfillment-policiesid-get
      parameters:
      - in: query
        name: credentialsId
        description: The ID of credentials for which to get the policy
      - in: path
        name: id
      - in: query
        name: marketplaceId
        description: The ID of the marketplace for which to get the policy
      responses:
        200:
          description: OK
      tags:
      - Fulfillment
      - Policy
  /rest/markets/ebay/payment_policies/{id}:
    get:
      summary: Get payment policy
      description: Get payment policy for given ID.
      operationId: getRestMarketsEbayPaymentPolicies
      x-api-path-slug: restmarketsebaypayment-policiesid-get
      parameters:
      - in: query
        name: credentialsId
        description: The ID of credentials for which to get the policy
      - in: path
        name: id
      - in: query
        name: marketplaceId
        description: The ID of the marketplace for which to get the policy
      responses:
        200:
          description: OK
      tags:
      - Payment
      - Policy
  /rest/markets/ebay/return_policies/{id}:
    get:
      summary: Get return policy
      description: Get return policy for given ID.
      operationId: getRestMarketsEbayReturnPolicies
      x-api-path-slug: restmarketsebayreturn-policiesid-get
      parameters:
      - in: query
        name: credentialsId
        description: The ID of credentials for which to get the policy
      - in: path
        name: id
      - in: query
        name: marketplaceId
        description: The ID of the marketplace for which to get the policy
      responses:
        200:
          description: OK
      tags:
      - Return
      - Policy
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