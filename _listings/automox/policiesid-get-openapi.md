---
swagger: "2.0"
x-collection-name: Automox
x-complete: 0
info:
  title: Automox Get Policies
  description: Gets a specific `Policy` object for the authenticated user.
  termsOfService: https://www.automox.com/
  contact:
    name: support@automox.com
  version: 1.0.0
host: console.automox.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /policies:
    get:
      summary: Get Policies
      description: Gets all `Policy` objects for authenticated user
      operationId: gets-all-policy-objects-for-authenticated-user
      x-api-path-slug: policies-get
      parameters:
      - in: query
        name: o
        description: Organization ID
      responses:
        200:
          description: OK
      tags:
      - Policies
  /policies/{id}:
    get:
      summary: Get Policies
      description: Gets a specific `Policy` object for the authenticated user.
      operationId: gets-a-specific-policy-object-for-the-authenticated-user
      x-api-path-slug: policiesid-get
      parameters:
      - in: path
        name: id
        description: Policy ID
      - in: query
        name: o
        description: Organization ID
      responses:
        200:
          description: OK
      tags:
      - Policies
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