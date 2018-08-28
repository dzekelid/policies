---
name: AWS Identity and Access Management
x-slug: aws-identity-and-access-management
description: AWS Identity and Access Management (IAM) enables you to securely control
  access to AWS services and resources for your users. Using IAM, you can create and
  manage AWS users and groups, and use permissions to allow and deny their access
  to AWS resources.IAM is a feature of your AWS account offered at no additional charge.
  You will be charged only for use of other AWS services by your users.To get started
  using IAM, orif you have already registered with AWS, go to theAWS Management Consoleand
  get started with theseIAM Best Practices.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Policies
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Identity and Access Management API - Create Policy
  x-api-slug: actioncreatepolicy-get
  description: Creates a new managed policy for your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actioncreatepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Create Policy Version
  x-api-slug: actioncreatepolicyversion-get
  description: Creates a new version of the specified managed policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actioncreatepolicyversion-get-openapi.md
- name: AWS Identity and Access Management API - Delete Policy
  x-api-slug: actiondeletepolicy-get
  description: Deletes the specified managed policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondeletepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Delete Policy Version
  x-api-slug: actiondeletepolicyversion-get
  description: Deletes the specified version from the specified managed policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondeletepolicyversion-get-openapi.md
- name: AWS Identity and Access Management API - Get Policy
  x-api-slug: actiongetpolicy-get
  description: |-
    Retrieves information about the specified managed policy, including the policy's
          default version and the total number of IAM users, groups, and roles to which the policy is
          attached.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetpolicy-get-openapi.md
- name: AWS Identity and Access Management API - Get Policy Version
  x-api-slug: actiongetpolicyversion-get
  description: |-
    Retrieves information about the specified version of the specified managed policy,
          including the policy document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetpolicyversion-get-openapi.md
- name: AWS Identity and Access Management API - List Attached Group Policies
  x-api-slug: actionlistattachedgrouppolicies-get
  description: Lists all managed policies that are attached to the specified IAM group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistattachedgrouppolicies-get-openapi.md
- name: AWS Identity and Access Management API - List Attached Role Policies
  x-api-slug: actionlistattachedrolepolicies-get
  description: Lists all managed policies that are attached to the specified IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistattachedrolepolicies-get-openapi.md
- name: AWS Identity and Access Management API - List Attached User Policies
  x-api-slug: actionlistattacheduserpolicies-get
  description: Lists all managed policies that are attached to the specified IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistattacheduserpolicies-get-openapi.md
- name: AWS Identity and Access Management API - List Group Policies
  x-api-slug: actionlistgrouppolicies-get
  description: |-
    Lists the names of the inline policies that are embedded in the specified IAM
          group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistgrouppolicies-get-openapi.md
- name: AWS Identity and Access Management API - List Policies
  x-api-slug: actionlistpolicies-get
  description: |-
    Lists all the managed policies that are available in your AWS account, including your
          own customer-defined managed policies and all AWS managed policies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistpolicies-get-openapi.md
- name: AWS Identity and Access Management API - List Role Policies
  x-api-slug: actionlistrolepolicies-get
  description: |-
    Lists the names of the inline policies that are embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistrolepolicies-get-openapi.md
- name: AWS Identity and Access Management API - List User Policies
  x-api-slug: actionlistuserpolicies-get
  description: Lists the names of the inline policies embedded in the specified IAM
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistuserpolicies-get-openapi.md
- name: AWS Identity and Access Management API - Attach Group Policy
  x-api-slug: actionattachgrouppolicy-get
  description: Attaches the specified managed policy to the specified IAM group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionattachgrouppolicy-get-openapi.md
- name: AWS Identity and Access Management API - Attach Role Policy
  x-api-slug: actionattachrolepolicy-get
  description: Attaches the specified managed policy to the specified IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionattachrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Attach User Policy
  x-api-slug: actionattachuserpolicy-get
  description: Attaches the specified managed policy to the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionattachuserpolicy-get-openapi.md
- name: AWS Identity and Access Management API - Create Policy
  x-api-slug: actioncreatepolicy-get
  description: Creates a new managed policy for your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actioncreatepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Create Policy Version
  x-api-slug: actioncreatepolicyversion-get
  description: Creates a new version of the specified managed policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actioncreatepolicyversion-get-openapi.md
- name: AWS Identity and Access Management API - Delete Account Password Policy
  x-api-slug: actiondeleteaccountpasswordpolicy-get
  description: Deletes the password policy for the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondeleteaccountpasswordpolicy-get-openapi.md
- name: AWS Identity and Access Management API - Delete Group Policy
  x-api-slug: actiondeletegrouppolicy-get
  description: |-
    Deletes the specified inline policy that is embedded in the specified IAM
          group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondeletegrouppolicy-get-openapi.md
- name: AWS Identity and Access Management API - Delete Policy
  x-api-slug: actiondeletepolicy-get
  description: Deletes the specified managed policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondeletepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Delete Policy Version
  x-api-slug: actiondeletepolicyversion-get
  description: Deletes the specified version from the specified managed policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondeletepolicyversion-get-openapi.md
- name: AWS Identity and Access Management API - Delete Role Policy
  x-api-slug: actiondeleterolepolicy-get
  description: |-
    Deletes the specified inline policy that is embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondeleterolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Delete User Policy
  x-api-slug: actiondeleteuserpolicy-get
  description: |-
    Deletes the specified inline policy that is embedded in the specified IAM
          user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondeleteuserpolicy-get-openapi.md
- name: AWS Identity and Access Management API - Detach Group Policy
  x-api-slug: actiondetachgrouppolicy-get
  description: Removes the specified managed policy from the specified IAM group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondetachgrouppolicy-get-openapi.md
- name: AWS Identity and Access Management API - Detach Role Policy
  x-api-slug: actiondetachrolepolicy-get
  description: Removes the specified managed policy from the specified role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondetachrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Detach User Policy
  x-api-slug: actiondetachuserpolicy-get
  description: Removes the specified managed policy from the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondetachuserpolicy-get-openapi.md
- name: AWS Identity and Access Management API - Get Account Password Policy
  x-api-slug: actiongetaccountpasswordpolicy-get
  description: Retrieves the password policy for the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetaccountpasswordpolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetaccountpasswordpolicy-get-openapi.md
- name: AWS Identity and Access Management API - Get Context Keys For Custom Policy
  x-api-slug: actiongetcontextkeysforcustompolicy-get
  description: Gets a list of all of the context keys referenced in the input policies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetcontextkeysforcustompolicy-get-openapi.md
- name: AWS Identity and Access Management API - Get Context Keys For Principal Policy
  x-api-slug: actiongetcontextkeysforprincipalpolicy-get
  description: |-
    Gets a list of all of the context keys referenced in all of the IAM policies attached
          to the specified IAM entity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetcontextkeysforprincipalpolicy-get-openapi.md
- name: AWS Identity and Access Management API - Get Group Policy
  x-api-slug: actiongetgrouppolicy-get
  description: |-
    Retrieves the specified inline policy document that is embedded in the specified IAM
          group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetgrouppolicy-get-openapi.md
- name: AWS Identity and Access Management API - Get Policy
  x-api-slug: actiongetpolicy-get
  description: |-
    Retrieves information about the specified managed policy, including the policy's
          default version and the total number of IAM users, groups, and roles to which the policy is
          attached.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetpolicy-get-openapi.md
- name: AWS Identity and Access Management API - Get Policy Version
  x-api-slug: actiongetpolicyversion-get
  description: |-
    Retrieves information about the specified version of the specified managed policy,
          including the policy document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetpolicyversion-get-openapi.md
- name: AWS Identity and Access Management API - Get Role Policy
  x-api-slug: actiongetrolepolicy-get
  description: |-
    Retrieves the specified inline policy document that is embedded with the specified
          IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Get User Policy
  x-api-slug: actiongetuserpolicy-get
  description: |-
    Retrieves the specified inline policy document that is embedded in the specified IAM
          user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetuserpolicy-get-openapi.md
- name: AWS Identity and Access Management API - List Entities For Policy
  x-api-slug: actionlistentitiesforpolicy-get
  description: |-
    Lists all IAM users, groups, and roles that the specified managed policy is attached
          to.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistentitiesforpolicy-get-openapi.md
- name: AWS Identity and Access Management API - List Policy Versions
  x-api-slug: actionlistpolicyversions-get
  description: |-
    Lists information about the versions of the specified managed policy, including the
          version that is currently set as the policy's default version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistpolicyversions-get-openapi.md
- name: AWS Identity and Access Management API - Put Group Policy
  x-api-slug: actionputgrouppolicy-get
  description: |-
    Adds or updates an inline policy document that is embedded in the specified IAM
          group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionputgrouppolicy-get-openapi.md
- name: AWS Identity and Access Management API - Put Role Policy
  x-api-slug: actionputrolepolicy-get
  description: |-
    Adds or updates an inline policy document that is embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionputrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API - Put User Policy
  x-api-slug: actionputuserpolicy-get
  description: |-
    Adds or updates an inline policy document that is embedded in the specified IAM
          user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionputuserpolicy-get-openapi.md
- name: AWS Identity and Access Management API - Set Default Policy Version
  x-api-slug: actionsetdefaultpolicyversion-get
  description: |-
    Sets the specified version of the specified policy as the policy's default (operative)
          version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionsetdefaultpolicyversion-get-openapi.md
- name: AWS Identity and Access Management API - Simulate Custom Policy
  x-api-slug: actionsimulatecustompolicy-get
  description: |-
    Simulate how a set of IAM policies and optionally a resource-based policy works with
          a list of API actions and AWS resources to determine the policies' effective permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionsimulatecustompolicy-get-openapi.md
- name: AWS Identity and Access Management API - Simulate Principal Policy
  x-api-slug: actionsimulateprincipalpolicy-get
  description: |-
    Simulate how a set of IAM policies attached to an IAM entity works with a list of
          API actions and AWS resources to determine the policies' effective permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionsimulateprincipalpolicy-get-openapi.md
- name: AWS Identity and Access Management API - Update Account Password Policy
  x-api-slug: actionupdateaccountpasswordpolicy-get
  description: Updates the password policy settings for the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionupdateaccountpasswordpolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionupdateaccountpasswordpolicy-get-openapi.md
- name: AWS Identity and Access Management API - Update Assume Role Policy
  x-api-slug: actionupdateassumerolepolicy-get
  description: Updates the policy that grants an IAM entity permission to assume a
    role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionupdateassumerolepolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionupdateassumerolepolicy-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.glacier.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.identity.and.access.management.stack.network
- type: x-change-log
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=323
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/sts/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/IAM/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/iam/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=76
- type: x-getting-started
  url: https://aws.amazon.com/iam/getting-started/
- type: x-partners
  url: https://aws.amazon.com/iam/partners/
- type: x-tools
  url: http://aws.amazon.com/cli
- type: x-website
  url: https://aws.amazon.com/iam/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---