---
swagger: "2.0"
x-collection-name: AWS Route 53
x-complete: 0
info:
  title: AWS Route 53 API Create Traffic Policy
  version: 1.0.0
  description: Creates a traffic policy, which you use to create multiple DNS resource
    record sets forone domain name (such as example.com) or one subdomain name (such
    aswww.example.com).Send a POST request to the /2013-04-01/trafficpolicy resource.
    The request body must include a documentwith a CreateTrafficPolicyRequest element.
    The response includes theCreateTrafficPolicyResponse element, which contains information
    about the newtraffic policy.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /2013-04-01/trafficpolicies&amp;maxitems=MaxItems?trafficpolicyid=TrafficPolicyIdMarker:
    get:
      summary: List Traffic Policies
      description: 'Gets information about the latest version for every traffic policy
        that is associatedwith the current AWS account. Send a GET request to the
        /Amazon Route 53API version/trafficpolicy resource.Amazon Route 53 returns
        a maximum of 100 items in each response. If you have a lot of trafficpolicies,
        you can use the maxitems parameter to list them in groups of up to100.The
        response includes three values that help you navigate from one group ofmaxitems
        traffic policies to the next:             IsTruncated           If the value
        of IsTruncated in the response is true,there are more traffic policies associated
        with the current AWS account.If IsTruncated is false, this response includes
        the lasttraffic policy that is associated with the current account.             TrafficPolicyIdMarker           If
        IsTruncated is true,TrafficPolicyIdMarker is the ID of the first traffic policy
        in the nextgroup of MaxItems traffic policies. If you want to list more trafficpolicies,
        make another call to ListTrafficPolicies, and specify the value ofthe TrafficPolicyIdMarker
        element from the response in theTrafficPolicyIdMarker request parameter.If
        IsTruncated is false, theTrafficPolicyIdMarker element is omitted from the
        response.             MaxItems           The value that you specified for
        the MaxItems parameter in the requestthat produced the current response.'
      operationId: listtrafficpolicies
      x-api-path-slug: 20130401trafficpoliciesampmaxitemsmaxitemstrafficpolicyidtrafficpolicyidmarker-get
      parameters:
      - in: path
        name: maxitems
        description: (Optional) The maximum number of traffic policies to be included
          in the response bodyfor this request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Traffic Policies
  /2013-04-01/trafficpolicies/Id/versions&amp;maxitems=MaxItems?trafficpolicyversion=TrafficPolicyVersionMarker:
    get:
      summary: List Traffic Policy Versions
      description: 'Gets information about all of the versions for a specified traffic
        policy.Send a GET request to the /Amazon Route 53 APIversion/trafficpolicy
        resource and specify the ID of the traffic policyfor which you want to list
        versions.Amazon Route 53 returns a maximum of 100 items in each response.
        If you have a lot of trafficpolicies, you can use the maxitems parameter to
        list them in groups of up to100.The response includes three values that help
        you navigate from one group ofmaxitems traffic policies to the next:             IsTruncated           If
        the value of IsTruncated in the response is true,there are more traffic policy
        versions associated with the specified trafficpolicy.If IsTruncated is false,
        this response includes the lasttraffic policy version that is associated with
        the specified traffic policy.             TrafficPolicyVersionMarker           The
        ID of the next traffic policy version that is associated with the current
        AWSaccount. If you want to list more traffic policies, make another call toListTrafficPolicyVersions,
        and specify the value of theTrafficPolicyVersionMarker element in theTrafficPolicyVersionMarker
        request parameter.If IsTruncated is false, Amazon Route 53 omits theTrafficPolicyVersionMarker
        element from the response.             MaxItems           The value that you
        specified for the MaxItems parameter in the requestthat produced the current
        response.'
      operationId: listtrafficpolicyversions
      x-api-path-slug: 20130401trafficpoliciesidversionsampmaxitemsmaxitemstrafficpolicyversiontrafficpolicyversionmarker-get
      parameters:
      - in: path
        name: Id
        description: Specify the value of Id of the traffic policy for which you want
          to listall versions
        type: string
      responses:
        200:
          description: OK
      tags:
      - Traffic Policies
  /2013-04-01/trafficpolicy:
    post:
      summary: Create Traffic Policy
      description: Creates a traffic policy, which you use to create multiple DNS
        resource record sets forone domain name (such as example.com) or one subdomain
        name (such aswww.example.com).Send a POST request to the /2013-04-01/trafficpolicy
        resource. The request body must include a documentwith a CreateTrafficPolicyRequest
        element. The response includes theCreateTrafficPolicyResponse element, which
        contains information about the newtraffic policy.
      operationId: createtrafficpolicy
      x-api-path-slug: 20130401trafficpolicy-post
      parameters:
      - in: body
        name: Comment
        description: (Optional) Any comments that you want to include about the traffic
          policy
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: CreateTrafficPolicyRequest
        description: Root level tag for the CreateTrafficPolicyRequest parameters
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: Document
        description: The definition of this traffic policy in JSON format
        schema:
          $ref: '#/definitions/holder'
      - in: body
        name: Name
        description: The name of the traffic policy
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Traffic Policies
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