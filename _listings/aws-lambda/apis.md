---
name: AWS Lambda
x-slug: aws-lambda
description: AWS Lambda is a zero-administration compute platform for back-end web
  developers that runs your code for you in the AWScloudand provides you with a fine-grained
  pricing structure. AWS Lambda runs your back-end code on its own AWS compute fleet
  of Amazon Elastic Compute Cloud (Amazon EC2) instances across multiple Availability
  Zones in a region, which provides the high availability, security, performance,
  and scalability of the AWS infrastructure.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Policies
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-lambda/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Lambda API Get Policy
  x-api-slug: aws-lambda-api
  description: Returns the resource policy associated with the specified Lambda function.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: ://///?Action=GetPolicy
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-lambda/actiongetpolicy-get-openapi.md
- name: AWS Lambda API
  x-api-slug: aws-lambda-api
  description: AWS Lambda is a zero-administration compute platform for back-end web
    developers that runs your code for you in the AWScloudand provides you with a
    fine-grained pricing structure. AWS Lambda runs your back-end code on its own
    AWS compute fleet of Amazon Elastic Compute Cloud (Amazon EC2) instances across
    multiple Availability Zones in a region, which provides the high availability,
    security, performance, and scalability of the AWS infrastructure.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSLambda.png
  humanURL: http://docs.aws.amazon.com/lambda/
  baseURL: :///
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-lambda/openapi.md
x-common:
- type: x-authentication
  url: http://docs.aws.amazon.com/lambda/latest/dg/lambda-auth-and-access-control.html
- type: x-best-practices
  url: http://docs.aws.amazon.com/lambda/latest/dg/best-practices.html
- type: x-console
  url: https://console.aws.amazon.com/lambda
- type: x-documentation
  url: http://docs.aws.amazon.com/lambda/latest/dg/API_Reference.html
- type: x-faq
  url: https://aws.amazon.com/lambda/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=186
- type: x-getting-started
  url: https://aws.amazon.com/lambda/getting-started/
- type: x-logging
  url: http://docs.aws.amazon.com/lambda/latest/dg/logging-using-cloudtrail.html
- type: x-partners
  url: https://aws.amazon.com/lambda/partners/
- type: x-pricing
  url: https://aws.amazon.com/lambda/pricing/
- type: x-rate-limits
  url: http://docs.aws.amazon.com/lambda/latest/dg/limits.html
- type: x-road-map
  url: http://aws.amazon.com/releasenotes/
- type: x-use-cases
  url: http://docs.aws.amazon.com/lambda/latest/dg/use-cases.html
- type: x-website
  url: http://docs.aws.amazon.com/lambda/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---