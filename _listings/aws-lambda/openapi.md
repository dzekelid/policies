swagger: "2.0"
x-collection-name: AWS Lambda
x-complete: 1
info:
  title: AWS Lambda API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetPolicy:
    get:
      summary: Get Policy
      description: Returns the resource policy associated with the specified Lambda
        function.
      operationId: getPolicy
      x-api-path-slug: actiongetpolicy-get
      parameters:
      - in: query
        name: FunctionName
        description: Function name whose resource policy you want to retrieve
        type: string
      - in: query
        name: Qualifier
        description: You can specify this optional query parameter to specify a function
          version or an alias name in which case this API will return all permissions
          associated with the specific qualified ARN
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies