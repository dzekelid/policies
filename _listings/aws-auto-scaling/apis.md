---
name: AWS Auto Scaling
x-slug: aws-auto-scaling
description: Auto Scaling helps you maintain application availability and allows you
  to scale yourAmazon EC2capacity up or down automatically according to conditions
  you define. You can use Auto Scaling to help ensure that you are running your desired
  number of Amazon EC2 instances. Auto Scaling can also automatically increase the
  number of Amazon EC2 instances during demand spikes to maintain performance and
  decrease capacity during lulls to reduce costs. Auto Scaling is well suited both
  to applications that have stable demand patterns or that experience hourly, daily,
  or weekly variability in usage.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Policies
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-auto-scaling/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Auto Scaling API - Delete Policy
  x-api-slug: actiondeletepolicy-get
  description: Deletes the specified Auto Scaling policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-auto-scaling/actiondeletepolicy-get-openapi.md
- name: AWS Auto Scaling API - Describe Policies
  x-api-slug: actiondescribepolicies-get
  description: Describes the policies for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-auto-scaling/actiondescribepolicies-get-openapi.md
- name: AWS Auto Scaling API - Execute Policy
  x-api-slug: actionexecutepolicy-get
  description: Executes the specified policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-auto-scaling/actionexecutepolicy-get-openapi.md
- name: AWS Auto Scaling API - Delete Policy
  x-api-slug: actiondeletepolicy-get
  description: Deletes the specified Auto Scaling policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-auto-scaling/actiondeletepolicy-get-openapi.md
- name: AWS Auto Scaling API - Describe Termination Policy Types
  x-api-slug: actiondescribeterminationpolicytypes-get
  description: Describes the termination policies supported by Auto Scaling.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-auto-scaling/actiondescribeterminationpolicytypes-get-openapi.md
- name: AWS Auto Scaling API - Execute Policy
  x-api-slug: actionexecutepolicy-get
  description: Executes the specified policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-auto-scaling/actionexecutepolicy-get-openapi.md
- name: AWS Auto Scaling API - Put Scaling Policy
  x-api-slug: actionputscalingpolicy-get
  description: Creates or updates a policy for an Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Amazon Web Services, Compute, Performance, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-auto-scaling/actionputscalingpolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-auto-scaling/actionputscalingpolicy-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.appstream.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.auto.scaling.stack.network
- type: x-articles
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=100
- type: x-change-log
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=86
- type: x-code
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=85
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/autoscaling/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/AutoScaling/latest/APIReference/
- type: x-forum
  url: http://developer.amazonwebservices.com/connect/forum.jspa?forumID=30
- type: x-getting-started
  url: https://aws.amazon.com/autoscaling/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/autoscaling/pricing/
- type: x-service-health
  url: http://status.aws.amazon.com/
- type: x-website
  url: https://aws.amazon.com/autoscaling/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---