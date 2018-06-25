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
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Identity and Access Management API Attach Group Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Attaches the specified managed policy to the specified IAM group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=AttachGroupPolicy
  tags: Group Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionattachgrouppolicy-get-openapi.md
- name: AWS Identity and Access Management API Attach Role Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Attaches the specified managed policy to the specified IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=AttachRolePolicy
  tags: Role Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionattachrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API Attach User Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Attaches the specified managed policy to the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=AttachUserPolicy
  tags: User Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionattachuserpolicy-get-openapi.md
- name: AWS Identity and Access Management API Create Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Creates a new managed policy for your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreatePolicy
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actioncreatepolicy-get-openapi.md
- name: AWS Identity and Access Management API Create Policy Version
  x-api-slug: aws-identity-and-access-management-api
  description: Creates a new version of the specified managed policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=CreatePolicyVersion
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actioncreatepolicyversion-get-openapi.md
- name: AWS Identity and Access Management API Delete Account Password Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the password policy for the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteAccountPasswordPolicy
  tags: Account Password Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondeleteaccountpasswordpolicy-get-openapi.md
- name: AWS Identity and Access Management API Delete Group Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Deletes the specified inline policy that is embedded in the specified IAM
          group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteGroupPolicy
  tags: Group Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondeletegrouppolicy-get-openapi.md
- name: AWS Identity and Access Management API Delete Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the specified managed policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeletePolicy
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondeletepolicy-get-openapi.md
- name: AWS Identity and Access Management API Delete Policy Version
  x-api-slug: aws-identity-and-access-management-api
  description: Deletes the specified version from the specified managed policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeletePolicyVersion
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondeletepolicyversion-get-openapi.md
- name: AWS Identity and Access Management API Delete Role Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Deletes the specified inline policy that is embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteRolePolicy
  tags: Role Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondeleterolepolicy-get-openapi.md
- name: AWS Identity and Access Management API Delete User Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Deletes the specified inline policy that is embedded in the specified IAM
          user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DeleteUserPolicy
  tags: User Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondeleteuserpolicy-get-openapi.md
- name: AWS Identity and Access Management API Detach Group Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Removes the specified managed policy from the specified IAM group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DetachGroupPolicy
  tags: Group Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondetachgrouppolicy-get-openapi.md
- name: AWS Identity and Access Management API Detach Role Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Removes the specified managed policy from the specified role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DetachRolePolicy
  tags: Role Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondetachrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API Detach User Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Removes the specified managed policy from the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=DetachUserPolicy
  tags: User Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiondetachuserpolicy-get-openapi.md
- name: AWS Identity and Access Management API Get Context Keys For Custom Policy
  x-api-slug: aws-identity-and-access-management-api
  description: Gets a list of all of the context keys referenced in the input policies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetContextKeysForCustomPolicy
  tags: Context Keys For Custom Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetcontextkeysforcustompolicy-get-openapi.md
- name: AWS Identity and Access Management API Get Context Keys For Principal Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Gets a list of all of the context keys referenced in all of the IAM policies attached
          to the specified IAM entity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetContextKeysForPrincipalPolicy
  tags: Context Keys For Principal Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetcontextkeysforprincipalpolicy-get-openapi.md
- name: AWS Identity and Access Management API Get Group Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves the specified inline policy document that is embedded in the specified IAM
          group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetGroupPolicy
  tags: Group Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetgrouppolicy-get-openapi.md
- name: AWS Identity and Access Management API Get Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves information about the specified managed policy, including the policy's
          default version and the total number of IAM users, groups, and roles to which the policy is
          attached.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetPolicy
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetpolicy-get-openapi.md
- name: AWS Identity and Access Management API Get Policy Version
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves information about the specified version of the specified managed policy,
          including the policy document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetPolicyVersion
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetpolicyversion-get-openapi.md
- name: AWS Identity and Access Management API Get Role Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves the specified inline policy document that is embedded with the specified
          IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetRolePolicy
  tags: Role Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API Get User Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Retrieves the specified inline policy document that is embedded in the specified IAM
          user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=GetUserPolicy
  tags: User Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actiongetuserpolicy-get-openapi.md
- name: AWS Identity and Access Management API List Attached Group Policies
  x-api-slug: aws-identity-and-access-management-api
  description: Lists all managed policies that are attached to the specified IAM group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListAttachedGroupPolicies
  tags: Attached Group Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistattachedgrouppolicies-get-openapi.md
- name: AWS Identity and Access Management API List Attached Role Policies
  x-api-slug: aws-identity-and-access-management-api
  description: Lists all managed policies that are attached to the specified IAM role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListAttachedRolePolicies
  tags: Attached Role Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistattachedrolepolicies-get-openapi.md
- name: AWS Identity and Access Management API List Attached User Policies
  x-api-slug: aws-identity-and-access-management-api
  description: Lists all managed policies that are attached to the specified IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListAttachedUserPolicies
  tags: Attached Use rPolicies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistattacheduserpolicies-get-openapi.md
- name: AWS Identity and Access Management API List Entities For Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Lists all IAM users, groups, and roles that the specified managed policy is attached
          to.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListEntitiesForPolicy
  tags: Entities For Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistentitiesforpolicy-get-openapi.md
- name: AWS Identity and Access Management API List Group Policies
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Lists the names of the inline policies that are embedded in the specified IAM
          group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListGroupPolicies
  tags: Group Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistgrouppolicies-get-openapi.md
- name: AWS Identity and Access Management API List Policies
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Lists all the managed policies that are available in your AWS account, including your
          own customer-defined managed policies and all AWS managed policies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListPolicies
  tags: listPolicies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistpolicies-get-openapi.md
- name: AWS Identity and Access Management API List Role Policies
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Lists the names of the inline policies that are embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListRolePolicies
  tags: Role Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistrolepolicies-get-openapi.md
- name: AWS Identity and Access Management API List User Policies
  x-api-slug: aws-identity-and-access-management-api
  description: Lists the names of the inline policies embedded in the specified IAM
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=ListUserPolicies
  tags: User Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionlistuserpolicies-get-openapi.md
- name: AWS Identity and Access Management API Put Group Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Adds or updates an inline policy document that is embedded in the specified IAM
          group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=PutGroupPolicy
  tags: Group Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionputgrouppolicy-get-openapi.md
- name: AWS Identity and Access Management API Put Role Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Adds or updates an inline policy document that is embedded in the specified IAM
          role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=PutRolePolicy
  tags: Role Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionputrolepolicy-get-openapi.md
- name: AWS Identity and Access Management API Put User Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Adds or updates an inline policy document that is embedded in the specified IAM
          user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=PutUserPolicy
  tags: Users Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionputuserpolicy-get-openapi.md
- name: AWS Identity and Access Management API Simulate Custom Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Simulate how a set of IAM policies and optionally a resource-based policy works with
          a list of API actions and AWS resources to determine the policies' effective permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=SimulateCustomPolicy
  tags: Custom Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionsimulatecustompolicy-get-openapi.md
- name: AWS Identity and Access Management API Simulate Principal Policy
  x-api-slug: aws-identity-and-access-management-api
  description: |-
    Simulate how a set of IAM policies attached to an IAM entity works with a list of
          API actions and AWS resources to determine the policies' effective permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: ://///?Action=SimulatePrincipalPolicy
  tags: Principal Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/actionsimulateprincipalpolicy-get-openapi.md
- name: AWS Identity and Access Management API
  x-api-slug: aws-identity-and-access-management-api
  description: AWS Identity and Access Management (IAM) enables you to securely control
    access to AWS services and resources for your users. Using IAM, you can create
    and manage AWS users and groups, and use permissions to allow and deny their access
    to AWS resources.IAM is a feature of your AWS account offered at no additional
    charge. You will be charged only for use of other AWS services by your users.To
    get started using IAM, orif you have already registered with AWS, go to theAWS
    Management Consoleand get started with theseIAM Best Practices.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/aws-identity-and-access-management/openapi.md
x-common:
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