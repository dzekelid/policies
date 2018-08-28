swagger: "2.0"
x-collection-name: AWS Elastic MapReduce
x-complete: 1
info:
  title: AWS Elastic MapReduce API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=PutAutoScalingPolicy:
    get:
      summary: Put Auto Scaling Policy
      description: Creates or updates an automatic scaling policy for a core instance
        group or task instance group in an Amazon EMR cluster.
      operationId: putAutoScalingPolicy
      x-api-path-slug: actionputautoscalingpolicy-get
      parameters:
      - in: query
        name: AutoScalingPolicy
        description: Specifies the definition of the automatic scaling policy
        type: string
      - in: query
        name: ClusterId
        description: Specifies the ID of a cluster
        type: string
      - in: query
        name: InstanceGroupId
        description: Specifies the ID of the instance group to which the automatic
          scaling policy is applied
        type: string
      responses:
        200:
          description: OK
      tags:
      - Auto Scaling Policies
  /?Action=RemoveAutoScalingPolicy:
    get:
      summary: Remove Auto Scaling Policy
      description: Removes an automatic scaling policy from a specified instance group
        within an EMR cluster.
      operationId: removeAutoScalingPolicy
      x-api-path-slug: actionremoveautoscalingpolicy-get
      parameters:
      - in: query
        name: ClusterId
        description: Specifies the ID of a cluster
        type: string
      - in: query
        name: InstanceGroupId
        description: Specifies the ID of the instance group to which the scaling policy
          is applied
        type: string
      responses:
        200:
          description: OK
      tags:
      - Auto Scaling Policies