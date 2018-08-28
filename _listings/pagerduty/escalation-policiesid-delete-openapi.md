---
swagger: "2.0"
x-collection-name: PagerDuty
x-complete: 0
info:
  title: PagerDuty Delete an escalation policy
  version: 1.0.0
  description: Deletes an existing escalation policy and rules. The escalation policy
    must not be in use by any services.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /escalation_policies:
    get:
      summary: List escalation policies
      description: List all of the existing escalation policies.
      operationId: list-all-of-the-existing-escalation-policies
      x-api-path-slug: escalation-policies-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: query
        description: Filters the results, showing only the escalation policies whose
          names contain the query
      - in: query
        name: user_ids[]
        description: Filters the results, showing only escalation policies on which
          any of the users is a target
      responses:
        200:
          description: OK
      tags:
      - Escalation Policies
    post:
      summary: Create an escalation policy
      description: Creates a new escalation policy. There must be at least one existing
        escalation rule added to create a new escalation policy.
      operationId: creates-a-new-escalation-policy-there-must-be-at-least-one-existing-escalation-rule-added-to-create-
      x-api-path-slug: escalation-policies-post
      parameters:
      - in: body
        name: escalation_policy
        description: The escalation policy to be created
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Escalation Policies
  /escalation_policies/{id}:
    get:
      summary: Get an escalation policy
      description: Get information about an existing escalation policy and its rules.
      operationId: get-information-about-an-existing-escalation-policy-and-its-rules
      x-api-path-slug: escalation-policiesid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Escalation Policies
    delete:
      summary: Delete an escalation policy
      description: Deletes an existing escalation policy and rules. The escalation
        policy must not be in use by any services.
      operationId: deletes-an-existing-escalation-policy-and-rules-the-escalation-policy-must-not-be-in-use-by-any-serv
      x-api-path-slug: escalation-policiesid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Escalation Policies
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