---
name: VictorOps
x-slug: victorops
description: VictorOps incident managament software gives DevOps observability, collaboration,
  & real-time alerting, to build, deploy, & operate software. Learn more.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
x-kinRank: "8"
x-alexaRank: "196587"
tags: Policies
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apis.md
specificationVersion: "0.14"
apis:
- name: Victor Ops Get escalation policy info
  x-api-slug: victor-ops
  description: |-
    Retrieves a list of escalation policy information.
    This API may be called a maximum of once a minute
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/policies
  tags: Policies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1policies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1policies-get-openapi.md
- name: Victor Ops Get the available contact types
  x-api-slug: victor-ops
  description: |-
    Get the available contact types

    description: "Email Address", type: "email"
    description: "Phone Number", type: "phone"

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/policies/types/contacts
  tags: Policies,Types,Contacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1policiestypescontacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1policiestypescontacts-get-openapi.md
- name: Victor Ops Get the available notification types
  x-api-slug: victor-ops
  description: |-
    Get the available notification types

    description: "Send a push notification to all my devices", type: "push"
    description: "Send an email to an email address", type: "email"
    description: "Send an SMS to a phone number", type: "sms"
    description: "Make a phone call to a phone number", type: "phone"

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/policies/types/notifications
  tags: Policies,Types,Notifications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1policiestypesnotifications-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1policiestypesnotifications-get-openapi.md
- name: Victor Ops Get the available timeout values
  x-api-slug: victor-ops
  description: |-
    Get the available timeout values

    description: "If still unacked after 1 minute", type: 1
    description: "If still unacked after 5 minutes", type: 5
    description: "If still unacked after 10 minutes", type: 10
    description: "If still unacked after 15 minutes", type: 15
    description: "If still unacked after 20 minutes", type: 20
    description: "If still unacked after 25 minutes", type: 25
    description: "If still unacked after 30 minutes", type: 30
    description: "If still unacked after 45 minutes", type: 45
    description: "If still unacked after 60 minutes", type: 60

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/policies/types/timeouts
  tags: Policies,Types,Timeouts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1policiestypestimeouts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1policiestypestimeouts-get-openapi.md
- name: Victor Ops Create an on-call override (take on-call)
  x-api-slug: victor-ops
  description: |-
    Replaces a currently on-call user in the escalation policy with another.  In many cases, the policy slug
    will match the slug of the team that contains it.

    This API may be called a maximum of 6 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/policies/{policy}/oncall/user
  tags: Policies,Policy,Oncall,User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1policiespolicyoncalluser-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1policiespolicyoncalluser-patch-openapi.md
- name: Victor Ops Get the user's paging policy
  x-api-slug: victor-ops
  description: |-
    Get all the paging policy steps for the user on the org associated with the API key

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/profile/{username}/policies
  tags: Profile,Username,Policies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepolicies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepolicies-get-openapi.md
- name: Victor Ops Create a paging policy step
  x-api-slug: victor-ops
  description: |-
    Create a paging policy step

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/profile/{username}/policies
  tags: Profile,Username,Policies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepolicies-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepolicies-post-openapi.md
- name: Victor Ops Get a paging policy step
  x-api-slug: victor-ops
  description: |-
    Get a paging policy step

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/profile/{username}/policies/{step}
  tags: Profile,Username,Policies,Step
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepoliciesstep-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepoliciesstep-get-openapi.md
- name: Victor Ops Create a rule for a paging policy step
  x-api-slug: victor-ops
  description: |-
    Create a rule for a paging policy step

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/profile/{username}/policies/{step}
  tags: Profile,Username,Policies,Step
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepoliciesstep-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepoliciesstep-post-openapi.md
- name: Victor Ops Update a paging policy step
  x-api-slug: victor-ops
  description: |-
    Update a paging policy step

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/profile/{username}/policies/{step}
  tags: Profile,Username,Policies,Step
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepoliciesstep-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepoliciesstep-put-openapi.md
- name: Victor Ops Delete a rule from a paging policy step
  x-api-slug: victor-ops
  description: |-
    Delete a rule from a paging policy step

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/profile/{username}/policies/{step}/{rule}
  tags: Profile,Username,Policies,Step,Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepoliciessteprule-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepoliciessteprule-delete-openapi.md
- name: Victor Ops Get a rule from a paging policy step
  x-api-slug: victor-ops
  description: |-
    Get a rule from a paging policy step

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/profile/{username}/policies/{step}/{rule}
  tags: Profile,Username,Policies,Step,Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepoliciessteprule-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepoliciessteprule-get-openapi.md
- name: Victor Ops Update a rule for a paging policy step
  x-api-slug: victor-ops
  description: |-
    Update a rule for a paging policy step

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/profile/{username}/policies/{step}/{rule}
  tags: Profile,Username,Policies,Step,Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepoliciessteprule-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1profileusernamepoliciessteprule-put-openapi.md
- name: Victor Ops Retrieve a list of escalation policies for a team
  x-api-slug: victor-ops
  description: |-
    Get the escalation policies for the specified team.

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/team/{team}/policies
  tags: Team,Team,Policies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1teamteampolicies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1teamteampolicies-get-openapi.md
- name: Victor Ops Get a list of paging policies for a user
  x-api-slug: victor-ops
  description: |-
    Get paging policies for a user

    This API may be called a maximum of 15 times per minute.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com////api-public/v1/user/{user}/policies
  tags: User,User,Policies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1useruserpolicies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/apipublicv1useruserpolicies-get-openapi.md
- name: Victor Ops
  x-api-slug: victor-ops
  description: VictorOps incident managament software gives DevOps observability,
    collaboration, & real-time alerting, to build, deploy, & operate software. Learn
    more.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20023-victorops.jpg
  humanURL: http://victorops.com
  baseURL: https://api.victorops.com//
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/victorops/openapi.md
x-common:
- type: x-blog
  url: https://victorops.com/blog/
- type: x-blog-rss
  url: https://victorops.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/victorops
- type: x-email
  url: support@victorops.com
- type: x-email
  url: info@victorops.com
- type: x-email
  url: press@victorops.com
- type: x-email
  url: sales@victorops.com
- type: x-github
  url: https://github.com/victorops
- type: x-pricing
  url: https://victorops.com/pricing/
- type: x-twitter
  url: https://twitter.com/VictorOps
- type: x-website
  url: http://victorops.com
- type: x-website
  url: https://victorops.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---