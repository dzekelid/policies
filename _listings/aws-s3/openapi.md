swagger: "2.0"
x-collection-name: AWS S3
x-complete: 1
info:
  title: No Title
  version: 1.0.0
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