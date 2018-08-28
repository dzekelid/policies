---
swagger: "2.0"
x-collection-name: AWS EC2 Container Registry Service
x-complete: 0
info:
  title: AWS EC2 Container Registry API Set Repository Policy
  version: 1.0.0
  description: Applies a repository policy on a specified repository to control access
    permissions.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteRepositoryPolicy:
    get:
      summary: Delete Repository Policy
      description: Deletes the repository policy from a specified repository.
      operationId: deleteRepositoryPolicy
      x-api-path-slug: actiondeleterepositorypolicy-get
      parameters:
      - in: query
        name: registryId
        description: The AWS account ID associated with the registry that contains
          the repository policy to delete
        type: string
      - in: query
        name: repositoryName
        description: The name of the repository that is associated with the repository
          policy to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Repository Policies
  /?Action=GetRepositoryPolicy:
    get:
      summary: Get Repository Policy
      description: Retrieves the repository policy for a specified repository.
      operationId: getRepositoryPolicy
      x-api-path-slug: actiongetrepositorypolicy-get
      parameters:
      - in: query
        name: registryId
        description: The AWS account ID associated with the registry that contains
          the repository
        type: string
      - in: query
        name: repositoryName
        description: The name of the repository whose policy you want to retrieve
        type: string
      responses:
        200:
          description: OK
      tags:
      - Repository Policies
  /?Action=SetRepositoryPolicy:
    get:
      summary: Set Repository Policy
      description: Applies a repository policy on a specified repository to control
        access permissions.
      operationId: setRepositoryPolicy
      x-api-path-slug: actionsetrepositorypolicy-get
      parameters:
      - in: query
        name: force
        description: If the policy you are attempting to set on a repository policy
          would prevent you from            setting another policy in the future,
          you must force the SetRepositoryPolicy            operation
        type: string
      - in: query
        name: policyText
        description: The JSON repository policy text to apply to the repository
        type: string
      - in: query
        name: registryId
        description: The AWS account ID associated with the registry that contains
          the repository
        type: string
      - in: query
        name: repositoryName
        description: The name of the repository to receive the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Repository Policies
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