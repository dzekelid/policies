{
  "info": {
    "name": "Plentymarkets Get fulfillment policy",
    "_postman_id": "deda372b-5515-427f-bdf1-0b8d11daeabf",
    "description": "Get fulfillment policy for given ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Fulfillment",
      "item": [
        {
          "id": "ad29695b-7f41-42c0-954d-d241003a50af",
          "name": "getRestMarketsEbayFulfillmentPolicies",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/markets/ebay/fulfillment_policies/:id"
              ],
              "query": [
                {
                  "key": "credentialsId",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "marketplaceId",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get fulfillment policy for given ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78e15af9-65c7-4be1-a55d-8be460d258d0"
            }
          ]
        }
      ]
    }
  ]
}