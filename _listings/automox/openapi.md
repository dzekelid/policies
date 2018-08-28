swagger: "2.0"
x-collection-name: Automox
x-complete: 1
info:
  title: Automox API
  description: the-automox-api-is-a-powerful-interface-that-allows-you-to-integrate-automox-reporting-data-into-you-applications-and-control-the-various-settings-of-your-account-all-endpoints-are-only-accessible-via-https-and-are-located-atapi-automox-com--for-instance-you-can-see-events-associated-with-your-account-by-accessing-the-following-url-with-your-idreplace-apikey-with-your-own--httpsconsole-automox-comapieventsapi-keyapikey-limitsbe-nice--if-youre-sending-too-many-requests-too-quickly-well-send-back-a429-error-code-too-many-requests-you-are-limited-to-5000-requests-per-hour-per-api-key-overall--practically-this-means-you-should-when-possible-authenticateusers-so-that-limits-are-well-outside-the-reach-of-a-given-user-
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
    put:
      summary: Put Policies
      description: Updates a `Policy` object
      operationId: updates-a-policy-object
      x-api-path-slug: policiesid-put
      parameters:
      - in: path
        name: id
        description: Policy ID
      - in: query
        name: o
        description: Organization ID
      - in: body
        name: policy
        description: Updated policy object
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Policies
  /policies/{id}/action:
    post:
      summary: Post Policies Action
      description: Schedule a policy for immediate remediation
      operationId: schedule-a-policy-for-immediate-remediation
      x-api-path-slug: policiesidaction-post
      parameters:
      - in: formData
        name: action
        description: Remediation action type [remediateAll]
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
      - Action