---
name: Automox
x-slug: automox
description: Patch any System, any Software, in Any Location with Automox. Our cloud-based
  patching management software was built for todays IT professionals.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28761-docs-automox-com.jpg
x-kinRank: "7"
x-alexaRank: "878532"
tags: Policies
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/automox/apis.md
specificationVersion: "0.14"
apis:
- name: Automox API - Get Policies
  x-api-slug: policies-get
  description: Gets all `Policy` objects for authenticated user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28761-docs-automox-com.jpg
  humanURL: https://automox.com
  baseURL: https://console.automox.com//api
  tags: SaaS, Technology, Enterprise, Operations, Servers, Security, Service API,
    Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/automox/policies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/automox/policies-get-openapi.md
- name: Automox API - Get Policies
  x-api-slug: policiesid-get
  description: Gets a specific `Policy` object for the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28761-docs-automox-com.jpg
  humanURL: https://automox.com
  baseURL: https://console.automox.com//api
  tags: SaaS, Technology, Enterprise, Operations, Servers, Security, Service API,
    Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/automox/policiesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/automox/policiesid-get-openapi.md
- name: Automox API - Put Policies
  x-api-slug: policiesid-put
  description: Updates a `Policy` object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28761-docs-automox-com.jpg
  humanURL: https://automox.com
  baseURL: https://console.automox.com//api
  tags: SaaS, Technology, Enterprise, Operations, Servers, Security, Service API,
    Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/automox/policiesid-put-openapi.md
- name: Automox API - Post Policies Action
  x-api-slug: policiesidaction-post
  description: Schedule a policy for immediate remediation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28761-docs-automox-com.jpg
  humanURL: https://automox.com
  baseURL: https://console.automox.com//api
  tags: SaaS, Technology, Enterprise, Operations, Servers, Security, Service API,
    Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/automox/policiesidaction-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://autodesk.api.gallery.streamdata.io
- type: x-api-stack
  url: http://automox.stack.network
- type: x-blog
  url: https://www.automox.com/blog
- type: x-crunchbase
  url: https://crunchbase.com/organization/automox
- type: x-documentation
  url: https://docs.automox.com/
- type: x-documentation
  url: https://docs.automox.com/api/
- type: x-email
  url: info@automox.com
- type: x-openapi
  url: https://docs.automox.com/api/swagger.yaml
- type: x-pricing
  url: https://www.automox.com/pricing
- type: x-support
  url: https://support.automox.com/hc/en-us
- type: x-twitter
  url: https://twitter.com/AutomoxApp
- type: x-website
  url: https://automox.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---