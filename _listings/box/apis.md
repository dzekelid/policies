---
name: Box
x-slug: box
description: Box is changing how you manage content across your business from simple
  file sharing to building custom apps.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
x-kinRank: "9"
x-alexaRank: "445"
tags: Policies
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/apis.md
specificationVersion: "0.14"
apis:
- name: Box Create Retention Policy
  x-api-slug: box
  description: Used to create a new retention policy.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//retention_policies
  tags: Documents,Retention, Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/retention-policies-post-openapi.md
- name: Box Get Retention Policies
  x-api-slug: box
  description: Retrieves all of the retention policies for the given enterprise.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//retention_policies
  tags: Documents,Retention, Policies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/retention-policies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/retention-policies-get-openapi.md
- name: Box Get Retention Policy
  x-api-slug: box
  description: Used to retrieve information about a retention policy
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//retention_policies/{POLICY_ID}
  tags: Documents,Retention, Policies, Policy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/retention-policiespolicy-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/retention-policiespolicy-id-get-openapi.md
- name: Box Update Retention Policy
  x-api-slug: box
  description: Used to update a retention policy.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//retention_policies/{POLICY_ID}
  tags: Documents,Retention, Policies, Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/retention-policiespolicy-id-put-openapi.md
- name: Box Get Retention Policy Assignments
  x-api-slug: box
  description: Returns a list of all retention policy assignments associated with
    a specified retention policy.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//retention_policies/{POLICY_ID}/assignments
  tags: Documents,Retention, Policies, Policy, , Assignments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/retention-policiespolicy-idassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/retention-policiespolicy-idassignments-get-openapi.md
- name: Box Create New Legal Hold Policy
  x-api-slug: box
  description: Create a new Legal Hold Policy. Optional date filter may be passed.
    If Policy has a date filter, any Custodian assignments will apply only to file
    versions created or uploaded inside of the date range.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//legal_hold_policies
  tags: Documents,Legal, Hold, Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/legal-hold-policies-post-openapi.md
- name: Box Get Legal Hold Policies
  x-api-slug: box
  description: Get a list of Legal Hold Policies that belong to your Enterprise.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//legal_hold_policies
  tags: Documents,Legal, Hold, Policies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/legal-hold-policies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/legal-hold-policies-get-openapi.md
- name: Box Update Existing Legal Hold Policy
  x-api-slug: box
  description: Update existing Legal Hold Policy. Only name and description can be
    modified.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//legal_hold_policies/{ID}
  tags: Documents,Legal, Hold, Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/legal-hold-policiesid-put-openapi.md
- name: Box Get Legal Hold Policy
  x-api-slug: box
  description: Get details of a single Legal Hold Policy
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//legal_hold_policies/{ID}
  tags: Documents,Legal, Hold, Policies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/legal-hold-policiesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/legal-hold-policiesid-get-openapi.md
- name: Box Delete Legal Hold Policy
  x-api-slug: box
  description: Sends request to delete an existing Legal Hold Policy. Note that this
    is an asynchronous process - the Policy will not be fully deleted yet when the
    response comes back.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//legal_hold_policies/{ID}
  tags: Documents,Legal, Hold, Policies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/legal-hold-policiesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/legal-hold-policiesid-delete-openapi.md
- name: Box Get Legal hold policy assignments
  x-api-slug: box
  description: Get list of assignments for a single Policy.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//legal_hold_policies/{ID}/assignments
  tags: Documents,Legal, Hold, Policies, , Assignments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/legal-hold-policiesidassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/legal-hold-policiesidassignments-get-openapi.md
- name: Box
  x-api-slug: box
  description: Box.net provides a sophisticated API for their online document sharing
    and collaboration web application.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/box/openapi.md
x-common:
- type: x-base
  url: https://api.box.com/
- type: x-blog
  url: http://blog.box.com/
- type: x-blog-rss
  url: http://blog.box.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/box
- type: x-crunchbase
  url: https://crunchbase.com/organization/box
- type: x-developer
  url: http://developers.box.com
- type: x-github
  url: https://github.com/boxdotnet
- type: x-pricing
  url: https://developers.box.com/box-platform-pricing/
- type: x-road-map
  url: https://developers.box.com/roadmap/
- type: x-twitter
  url: https://twitter.com/BoxPlatform
- type: x-twitter
  url: https://twitter.com/BoxHQ
- type: x-website
  url: http://box.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---