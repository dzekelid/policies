swagger: "2.0"
x-collection-name: AWS Elastic Load Balancing
x-complete: 1
info:
  title: AWS Elastic Load Balancing API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeSSLPolicies:
    get:
      summary: Describe S S L Policies
      description: Describes the specified policies or all policies used for SSL negotiation.
      operationId: describeSSLPolicies
      x-api-path-slug: actiondescribesslpolicies-get
      parameters:
      - in: query
        name: Marker
        description: The marker for the next set of results
        type: string
      - in: query
        name: Names.member.N
        description: The names of the policies
        type: string
      - in: query
        name: PageSize
        description: The maximum number of results to return with this call
        type: string
      responses:
        200:
          description: OK
      tags:
      - SSL Policies