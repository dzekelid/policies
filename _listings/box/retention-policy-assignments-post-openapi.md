---
swagger: "2.0"
x-collection-name: Box
x-complete: 0
info:
  title: Box Create Retention Policy Assignment
  description: Returns a list of all retention policy assignments associated with
    a specified retention policy.
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
    put:
      summary: Update Retention Policy
      description: Used to update a retention policy.
      operationId: updateRetentionPolicy
      x-api-path-slug: retention-policiespolicy-id-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
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
  /retention_policies/{POLICY_ID}/assignments:
    get:
      summary: Get Retention Policy Assignments
      description: Returns a list of all retention policy assignments associated with
        a specified retention policy.
      operationId: getRetentionPolicyAssignments
      x-api-path-slug: retention-policiespolicy-idassignments-get
      parameters:
      - in: path
        name: POLICY_ID
      - in: query
        name: type
        description: The type of the retention policy assignment to retrieve
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Retention
      - Policies
      - Policy
      - ""
      - Assignments
  /legal_hold_policies:
    post:
      summary: Create New Legal Hold Policy
      description: Create a new Legal Hold Policy. Optional date filter may be passed.
        If Policy has a date filter, any Custodian assignments will apply only to
        file versions created or uploaded inside of the date range.
      operationId: createLegalHoldPolicy
      x-api-path-slug: legal-hold-policies-post
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
      - Legal
      - Hold
      - Policies
    get:
      summary: Get Legal Hold Policies
      description: Get a list of Legal Hold Policies that belong to your Enterprise.
      operationId: getLegalHoldPolicies
      x-api-path-slug: legal-hold-policies-get
      parameters:
      - in: query
        name: limit
        description: Limit result size to this number
      - in: query
        name: marker
        description: Take from next_marker column of a prior call to get the next
          page
      - in: query
        name: policy_name
        description: Case insensitive prefix-match filter on Policy name
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Legal
      - Hold
      - Policies
  /legal_hold_policies/{ID}:
    put:
      summary: Update Existing Legal Hold Policy
      description: Update existing Legal Hold Policy. Only name and description can
        be modified.
      operationId: updateLegalHoldPolicy
      x-api-path-slug: legal-hold-policiesid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Legal
      - Hold
      - Policies
    get:
      summary: Get Legal Hold Policy
      description: Get details of a single Legal Hold Policy
      operationId: getLegalHoldPolicy
      x-api-path-slug: legal-hold-policiesid-get
      parameters:
      - in: path
        name: ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Legal
      - Hold
      - Policies
    delete:
      summary: Delete Legal Hold Policy
      description: Sends request to delete an existing Legal Hold Policy. Note that
        this is an asynchronous process - the Policy will not be fully deleted yet
        when the response comes back.
      operationId: deleteLegalHoldPolicy
      x-api-path-slug: legal-hold-policiesid-delete
      parameters:
      - in: path
        name: ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Legal
      - Hold
      - Policies
  /legal_hold_policies/{ID}/assignments:
    get:
      summary: Get Legal hold policy assignments
      description: Get list of assignments for a single Policy.
      operationId: getLegalHoldPolicyAssignments
      x-api-path-slug: legal-hold-policiesidassignments-get
      parameters:
      - in: path
        name: ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Legal
      - Hold
      - Policies
      - ""
      - Assignments
  /retention_policy_assignments:
    post:
      summary: Create Retention Policy Assignment
      description: Returns a list of all retention policy assignments associated with
        a specified retention policy.
      operationId: createRetentionPolicyAssignment
      x-api-path-slug: retention-policy-assignments-post
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
      - Policy
      - Assignments
  /retention_policy_assignments/{RETENTION_POLICY_ASSIGNMENT_ID}:
    get:
      summary: Get Retention Policy Assignment
      description: Used to retrieve information about a retention policy assignment.
      operationId: getRetentionPolicyAssignment
      x-api-path-slug: retention-policy-assignmentsretention-policy-assignment-id-get
      parameters:
      - in: path
        name: RETENTION_POLICY_ASSIGNMENT_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Retention
      - Policy
      - Assignments
      - Retention
      - Policy
      - Assignment
  /legal_hold_policy_assignments:
    post:
      summary: Create New Legal Hold Policy Assignment
      description: Create a new Assignment, which will apply the Legal Hold Policy
        to the target of the Assignment.
      operationId: createLegalHoldPolicyAssignment
      x-api-path-slug: legal-hold-policy-assignments-post
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
      - Legal
      - Hold
      - Policy
      - Assignments
  /legal_hold_policy_assignments/{ASSIGNMENT_ID}:
    get:
      summary: Get Legal Hold Policy Assignment
      description: Get details of a single assignment.
      operationId: getLegalHoldPolicyAssignment
      x-api-path-slug: legal-hold-policy-assignmentsassignment-id-get
      parameters:
      - in: path
        name: ASSIGNMENT_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Legal
      - Hold
      - Policy
      - Assignments
      - Assignment
    delete:
      summary: Delete Legal Hold Policy Assignment
      description: Sends request to delete an existing Assignment. Note that this
        is an asynchronous process - the Assignment will not be fully deleted yet
        when the response comes back.
      operationId: deleteLegalHoldPolicyAssignment
      x-api-path-slug: legal-hold-policy-assignmentsassignment-id-delete
      parameters:
      - in: path
        name: ASSIGNMENT_ID
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Legal
      - Hold
      - Policy
      - Assignments
      - Assignment
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