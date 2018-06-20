---
swagger: "2.0"
x-collection-name: Box
x-complete: 0
info:
  title: Box Get Retention Policy
  description: Used to retrieve information about a retention policy
  version: 1.0.0
host: api.box.com
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /retention_policies:
    post:
      summary: Create Retention Policy
      description: Used to create a new retention policy.
      operationId: createRetentionPolicy
      x-api-path-slug: retention-policies-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Retention
      - Policies
    get:
      summary: Get Retention Policies
      description: Retrieves all of the retention policies for the given enterprise.
      operationId: getRetentionPolicies
      x-api-path-slug: retention-policies-get
      parameters:
      - in: query
        name: created_by_user_id
        description: A user id to filter the retention policies by
      - in: query
        name: policy_name
        description: A name to filter the retention policies by
      - in: query
        name: policy_type
        description: A policy type to filter the retention policies by
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Retention
      - Policies
  /retention_policies/{POLICY_ID}:
    get:
      summary: Get Retention Policy
      description: Used to retrieve information about a retention policy
      operationId: getRetentionPolicy
      x-api-path-slug: retention-policiespolicy-id-get
      parameters:
      - in: path
        name: POLICY_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Retention
      - Policies
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