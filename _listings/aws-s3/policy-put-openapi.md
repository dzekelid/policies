---
swagger: "2.0"
x-collection-name: AWS S3
x-complete: 0
info:
  title: AWS S3 PUT Bucket policy
  version: 1.0.0
  description: This implementation of the PUT operation uses the policysubresource
    to add to or replace a policy on a bucket
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?policy:
    delete:
      summary: DELETE Bucket policy
      description: This implementation of the DELETE operation uses the policy subresource
        to delete the policy on a specified bucket
      operationId: delete-bucket-policy
      x-api-path-slug: policy-delete
      responses:
        200:
          description: OK
      tags:
      - Bucket
      - Policy
    get:
      summary: GET Bucket policy
      description: This implementation of the GET operation uses the policysubresource
        to return the policy of a specified bucket
      operationId: get-bucket-policy
      x-api-path-slug: policy-get
      responses:
        200:
          description: OK
      tags:
      - Bucket
      - Policy
    put:
      summary: PUT Bucket policy
      description: This implementation of the PUT operation uses the policysubresource
        to add to or replace a policy on a bucket
      operationId: put-bucket-policy
      x-api-path-slug: policy-put
      responses:
        200:
          description: OK
      tags:
      - Bucket
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