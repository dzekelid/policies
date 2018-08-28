{
  "info": {
    "name": "AWS Identity and Access Management API Update Account Password Policy",
    "_postman_id": "29955657-a1c2-402e-8969-940dd324b016",
    "description": "Updates the password policy settings for the AWS account.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "OpenID Connect Providers",
      "item": [
        {
          "id": "a9d710af-5bfa-4e98-9dc8-031ddab59966",
          "name": "addClientIDToOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=AddClientIDToOpenIDConnectProvider?ClientID=ClientID&OpenIDConnectProviderArn=OpenIDConnectProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds a new client ID (also known as audience) to the list of client IDs already\n      registered for the specified IAM OpenID Connect (OIDC) provider resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4292d1e8-31ab-48c4-b84e-b40207ad6e24"
            }
          ]
        },
        {
          "id": "2541144e-feb7-487c-88da-7d903525dd6b",
          "name": "createOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=CreateOpenIDConnectProvider?ClientIDList.member.N=ClientIDList.member.N&ThumbprintList.member.N=ThumbprintList.member.N&Url=Url",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an IAM entity to describe an identity provider (IdP) that supports."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1a13280-d677-4cea-9080-3914e85f3671"
            }
          ]
        },
        {
          "id": "9014b514-7efa-4efc-b3a4-f12da72d92d3",
          "name": "deleteOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=DeleteOpenIDConnectProvider?OpenIDConnectProviderArn=OpenIDConnectProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an OpenID Connect identity provider (IdP) resource object in IAM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f4c25ffb-9d8b-48f4-83a4-fc968e1edd7b"
            }
          ]
        },
        {
          "id": "81098bc2-22df-46a7-ab05-204ec895af6b",
          "name": "getOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=GetOpenIDConnectProvider?OpenIDConnectProviderArn=OpenIDConnectProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the specified OpenID Connect (OIDC) provider resource object\n      in IAM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c668c0e4-ebee-48b8-b778-ab933ae52315"
            }
          ]
        },
        {
          "id": "9800a225-7e78-49ee-bdba-fbaa7f454a5b",
          "name": "listOpenIDConnectProviders",
          "request": {
            "url": "http://example.com/api/?Action=ListOpenIDConnectProviders?OpenIDConnectProviderList.member.N=OpenIDConnectProviderList.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists information about the IAM OpenID Connect (OIDC) provider resource objects\n      defined in the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c98d9e0b-e99a-49a7-b275-981a80e881c5"
            }
          ]
        },
        {
          "id": "b337f73e-9784-4492-aa18-63edeb7343c9",
          "name": "removeClientIDFromOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=RemoveClientIDFromOpenIDConnectProvider?ClientID=ClientID&OpenIDConnectProviderArn=OpenIDConnectProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified client ID (also known as audience) from the list of client IDs\n      registered for the specified IAM OpenID Connect (OIDC) provider resource object."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9307a137-e8a5-4189-a3d0-a3058d605d0c"
            }
          ]
        }
      ]
    },
    {
      "name": "Role Instance",
      "item": [
        {
          "id": "7b2d2176-7c68-4ec0-a8e5-fee75a7d786d",
          "name": "addRoleToInstanceProfile",
          "request": {
            "url": "http://example.com/api/?Action=AddRoleToInstanceProfile?InstanceProfileName=InstanceProfileName&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the specified IAM role to the specified instance profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e85d6b2c-bcba-4139-9d9b-f1bb0695f0d7"
            }
          ]
        }
      ]
    },
    {
      "name": "User Groups",
      "item": [
        {
          "id": "3599911d-95a7-43bb-bb84-b4ca0c4a2026",
          "name": "addUserToGroup",
          "request": {
            "url": "http://example.com/api/?Action=AddUserToGroup?GroupName=GroupName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the specified user to the specified group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb8ae528-c1c9-493d-a7d1-751e0e615ace"
            }
          ]
        }
      ]
    },
    {
      "name": "Group Policies",
      "item": [
        {
          "id": "ba2296d7-36b7-46aa-9b24-b665a39df33f",
          "name": "attachGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=AttachGroupPolicy?GroupName=GroupName&PolicyArn=PolicyArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified managed policy to the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f9bec66-091b-4bc4-aada-c02c073a9ab4"
            }
          ]
        },
        {
          "id": "f57db746-b5b1-4b4c-9108-3f968037838c",
          "name": "deleteGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteGroupPolicy?GroupName=GroupName&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified inline policy that is embedded in the specified IAM\n      group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "73146f8e-8cf3-44b4-be77-aaa942549240"
            }
          ]
        },
        {
          "id": "fb8d93f2-90bc-4e5d-bf61-0a3537fffe41",
          "name": "detachGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DetachGroupPolicy?GroupName=GroupName&PolicyArn=PolicyArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified managed policy from the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d3ba1d5c-2d3a-4201-a8dc-7d48fa49d94a"
            }
          ]
        },
        {
          "id": "e5ad4075-f8eb-413f-b2a6-6b0bf90dca3a",
          "name": "getGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetGroupPolicy?GroupName=GroupName&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the specified inline policy document that is embedded in the specified IAM\n      group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9883075-3f82-4784-936f-027f199c4418"
            }
          ]
        },
        {
          "id": "61981476-8233-494c-a6b8-82bf2c8c832c",
          "name": "listGroupPolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListGroupPolicies?GroupName=GroupName&Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the names of the inline policies that are embedded in the specified IAM\n      group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "73b3e537-598d-4db2-b08e-558b8835b45d"
            }
          ]
        },
        {
          "id": "e8fa5173-82d9-4ac2-a210-c2f534887ded",
          "name": "putGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=PutGroupPolicy?GroupName=GroupName&PolicyDocument=PolicyDocument&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds or updates an inline policy document that is embedded in the specified IAM\n      group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4cc677f5-60e8-499a-aa62-0d4c7170f0bc"
            }
          ]
        }
      ]
    },
    {
      "name": "Role Policies",
      "item": [
        {
          "id": "3441b336-540a-4a05-8d1e-9a26420c3942",
          "name": "attachRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=AttachRolePolicy?PolicyArn=PolicyArn&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified managed policy to the specified IAM role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "504acddd-7e8b-4a4e-9dec-9b1dc24ddaa0"
            }
          ]
        },
        {
          "id": "a194a4e4-007a-42e6-9b5b-d846f1b1e08c",
          "name": "deleteRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRolePolicy?PolicyName=PolicyName&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified inline policy that is embedded in the specified IAM\n      role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96912150-a809-4c0a-a635-b5ca8af63f5e"
            }
          ]
        },
        {
          "id": "65a2ce2b-6d13-404e-b85a-04fb55fbf792",
          "name": "detachRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=DetachRolePolicy?PolicyArn=PolicyArn&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified managed policy from the specified role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3710ca84-f07e-4fda-8382-69354197f673"
            }
          ]
        },
        {
          "id": "252bafa1-26fa-4394-99d7-42f13d70a5a8",
          "name": "getRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetRolePolicy?PolicyName=PolicyName&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the specified inline policy document that is embedded with the specified\n      IAM role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f53d94ae-1bee-4ea2-97ce-fffb723d7f1a"
            }
          ]
        },
        {
          "id": "af9a5b31-af0b-4f72-9505-31c418999843",
          "name": "listRolePolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListRolePolicies?Marker=Marker&MaxItems=MaxItems&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the names of the inline policies that are embedded in the specified IAM\n      role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f48ae0ff-5566-455a-9644-f96d1a6de249"
            }
          ]
        },
        {
          "id": "8c59a24e-38b3-4e4b-94d3-856c62b9398a",
          "name": "putRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=PutRolePolicy?PolicyDocument=PolicyDocument&PolicyName=PolicyName&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds or updates an inline policy document that is embedded in the specified IAM\n      role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "41c524e3-134c-4621-a337-578b61ab317a"
            }
          ]
        }
      ]
    },
    {
      "name": "User Policies",
      "item": [
        {
          "id": "1117e706-69fa-42a6-bef3-78eee3a87ea3",
          "name": "attachUserPolicy",
          "request": {
            "url": "http://example.com/api/?Action=AttachUserPolicy?PolicyArn=PolicyArn&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified managed policy to the specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "10472343-6a69-4f49-81d6-d184ef448835"
            }
          ]
        },
        {
          "id": "93926f2e-e64f-4131-b2d5-0c83173c3ec4",
          "name": "deleteUserPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUserPolicy?PolicyName=PolicyName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified inline policy that is embedded in the specified IAM\n      user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aee8c660-8a83-4e27-b1e2-898871abf1a7"
            }
          ]
        },
        {
          "id": "c16b0089-feef-493b-8bd0-86311f6ccc73",
          "name": "detachUserPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DetachUserPolicy?PolicyArn=PolicyArn&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified managed policy from the specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f77c8d4d-b690-437c-a496-d22728c4cc23"
            }
          ]
        },
        {
          "id": "9c125c96-dab2-4f0d-90f1-96835b6d7ac8",
          "name": "getUserPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetUserPolicy?PolicyName=PolicyName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the specified inline policy document that is embedded in the specified IAM\n      user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "657a272c-4fd2-4891-8307-c5bac97803ea"
            }
          ]
        },
        {
          "id": "d9876c25-ba4f-46fb-8c97-12a4e48d10d7",
          "name": "listUserPolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListUserPolicies?Marker=Marker&MaxItems=MaxItems&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the names of the inline policies embedded in the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1685ad0-b6dd-43b9-b51c-043c42bd59f0"
            }
          ]
        }
      ]
    },
    {
      "name": "Passwords",
      "item": [
        {
          "id": "8d4aa0c0-82e0-450a-845a-b41643cfb8d1",
          "name": "changePassword",
          "request": {
            "url": "http://example.com/api/?Action=ChangePassword?NewPassword=NewPassword&OldPassword=OldPassword",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Changes the password of the IAM user who is calling this action."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f192d7b-b0bc-4057-9888-d7eceb66f0bd"
            }
          ]
        }
      ]
    },
    {
      "name": "Access Keys",
      "item": [
        {
          "id": "6d450d6f-7f16-4ced-a308-4103a12ce5f9",
          "name": "createAccessKey",
          "request": {
            "url": "http://example.com/api/?Action=CreateAccessKey?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new AWS secret access key and corresponding AWS access key ID for the\n      specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15e9f8a2-c76d-48c3-aecc-d0960fba383d"
            }
          ]
        },
        {
          "id": "c9aa485a-f986-4316-8708-e62acb6809d2",
          "name": "deleteAccessKey",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAccessKey?AccessKeyId=AccessKeyId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the access key pair associated with the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8cf39a6e-a1ef-4afb-875c-5fb8d4dd9ca9"
            }
          ]
        },
        {
          "id": "551c9688-7784-42dc-aee6-8da3e21c8ba0",
          "name": "getAccessKeyLastUsed",
          "request": {
            "url": "http://example.com/api/?Action=GetAccessKeyLastUsed?AccessKeyId=AccessKeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about when the specified access key was last used."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6973661-1e25-41ed-ad9e-d5ee8e36accb"
            }
          ]
        },
        {
          "id": "456661e9-e51b-4798-866b-3f28b2ddc46c",
          "name": "listAccessKeys",
          "request": {
            "url": "http://example.com/api/?Action=ListAccessKeys?Marker=Marker&MaxItems=MaxItems&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the access key IDs associated with the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38769614-33db-49ac-bfa5-4997d70b5c6f"
            }
          ]
        },
        {
          "id": "f1665dc5-197c-48f8-a917-b39d95794b65",
          "name": "updateAccessKey",
          "request": {
            "url": "http://example.com/api/?Action=UpdateAccessKey?AccessKeyId=AccessKeyId&Status=Status&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Changes the status of the specified access key from Active to Inactive, or vice versa."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de197e46-16a0-41d2-ab35-19f7f92f0401"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Alias",
      "item": [
        {
          "id": "0233a2b3-ed38-467f-9e40-78dcd580e237",
          "name": "createAccountAlias",
          "request": {
            "url": "http://example.com/api/?Action=CreateAccountAlias?AccountAlias=AccountAlias",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an alias for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4c59e471-7434-4f90-b1b0-4fcaa3025d26"
            }
          ]
        },
        {
          "id": "f38ac790-8592-4d57-a2ec-1c6ab93071cb",
          "name": "deleteAccountAlias",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAccountAlias?AccountAlias=AccountAlias",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified AWS account alias."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ebc8eb0-08e5-4cca-a36d-7b2124cc4e94"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "08ae55e6-8b2a-45d2-b403-7e22a55b3fb3",
          "name": "createGroup",
          "request": {
            "url": "http://example.com/api/?Action=CreateGroup?GroupName=GroupName&Path=Path",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1a26dd67-961a-445a-a7c4-ef1a94f1ea7c"
            }
          ]
        },
        {
          "id": "fd0844e3-b81b-4611-b205-c6c9f0f0f526",
          "name": "deleteGroup",
          "request": {
            "url": "http://example.com/api/?Action=DeleteGroup?GroupName=GroupName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "873ff695-073d-4576-af86-7b44c34631a0"
            }
          ]
        },
        {
          "id": "8252b6de-6f4d-4c3a-a63f-831d2bdaa60f",
          "name": "getGroup",
          "request": {
            "url": "http://example.com/api/?Action=GetGroup?GroupName=GroupName&Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of IAM users that are in the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15d6dbb6-5bcb-41c1-ab23-71c89ce4095a"
            }
          ]
        },
        {
          "id": "5098dd4d-bef7-4905-a08c-c63461c011b0",
          "name": "listGroups",
          "request": {
            "url": "http://example.com/api/?Action=ListGroups?Marker=Marker&MaxItems=MaxItems&PathPrefix=PathPrefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the IAM groups that have the specified path prefix."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "341e0839-8fdb-4bcc-aa92-c23324eea318"
            }
          ]
        }
      ]
    },
    {
      "name": "Instance Profiles",
      "item": [
        {
          "id": "a9090755-dddc-4320-99c0-4c6bbdf574ce",
          "name": "createInstanceProfile",
          "request": {
            "url": "http://example.com/api/?Action=CreateInstanceProfile?InstanceProfileName=InstanceProfileName&Path=Path",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new instance profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f9ddacb8-50da-47a1-b999-1e603f993905"
            }
          ]
        },
        {
          "id": "44029521-885a-4b9f-9691-171f48b5631a",
          "name": "deleteInstanceProfile",
          "request": {
            "url": "http://example.com/api/?Action=DeleteInstanceProfile?InstanceProfileName=InstanceProfileName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified instance profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fd0b148b-4299-4af4-a15e-33123f3adf0c"
            }
          ]
        },
        {
          "id": "78437923-19b8-4693-90d4-1647ec8d2993",
          "name": "getInstanceProfile",
          "request": {
            "url": "http://example.com/api/?Action=GetInstanceProfile?InstanceProfileName=InstanceProfileName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified instance profile, including the instance\n      profile's path, GUID, ARN, and role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "93a40155-42be-42da-a635-97075b689f8d"
            }
          ]
        },
        {
          "id": "318b77f3-dc0d-4ab7-8cbe-e1d7fa64fa0a",
          "name": "listInstanceProfiles",
          "request": {
            "url": "http://example.com/api/?Action=ListInstanceProfiles?Marker=Marker&MaxItems=MaxItems&PathPrefix=PathPrefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the instance profiles that have the specified path prefix."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "26bba6c4-83df-4a53-ab18-3d7d8b20fff0"
            }
          ]
        }
      ]
    },
    {
      "name": "Login Profiles",
      "item": [
        {
          "id": "c6b806ef-b681-4948-9c33-8e3535166760",
          "name": "createLoginProfile",
          "request": {
            "url": "http://example.com/api/?Action=CreateLoginProfile?Password=Password&PasswordResetRequired=PasswordResetRequired&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a password for the specified user, giving the user the ability to access AWS\n      services through the AWS Management Console."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "497034bb-e043-427f-bacb-dbab9ded0bb4"
            }
          ]
        },
        {
          "id": "8a42a493-9bd6-4635-815c-e21101250b83",
          "name": "deleteLoginProfile",
          "request": {
            "url": "http://example.com/api/?Action=DeleteLoginProfile?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the password for the specified IAM user, which terminates the user's ability\n      to access AWS services through the AWS Management Console."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7731b5f4-a668-408a-a3f3-7247c54254c1"
            }
          ]
        },
        {
          "id": "2d14183f-4b40-40d0-bbd0-c56606537c5f",
          "name": "getLoginProfile",
          "request": {
            "url": "http://example.com/api/?Action=GetLoginProfile?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the user name and password-creation date for the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6ef070e7-f720-42f5-83b2-9f2777536d09"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "e6ab4ba2-81dc-4c8f-bdb3-279e0f010663",
          "name": "createPolicy",
          "request": {
            "url": "http://example.com/api/?Action=CreatePolicy?Description=Description&Path=Path&PolicyDocument=PolicyDocument&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new managed policy for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f34d9765-b349-439d-a87d-85476726be28"
            }
          ]
        },
        {
          "id": "7a34481e-ff0c-4c06-81ea-dcfe6409ba0b",
          "name": "createPolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=CreatePolicyVersion?PolicyArn=PolicyArn&PolicyDocument=PolicyDocument&SetAsDefault=SetAsDefault",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new version of the specified managed policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c21a8aa5-60e3-4a2e-9ce3-f321d4f1fd94"
            }
          ]
        },
        {
          "id": "e77b93f4-9277-4ee1-a0ee-bce61d7bf7d8",
          "name": "deletePolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeletePolicy?PolicyArn=PolicyArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified managed policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e9aa5ec8-e2d1-4266-af01-9cbf3b2de020"
            }
          ]
        },
        {
          "id": "ed77fa1f-8e1f-417c-9f4e-5986c74b3143",
          "name": "deletePolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=DeletePolicyVersion?PolicyArn=PolicyArn&VersionId=VersionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified version from the specified managed policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "093d3412-7f71-4231-928d-2b7dff48683f"
            }
          ]
        },
        {
          "id": "af4f50bb-0545-4359-8395-4806323b006a",
          "name": "getPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetPolicy?PolicyArn=PolicyArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified managed policy, including the policy's\n      default version and the total number of IAM users, groups, and roles to which the policy is\n      attached."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "139fc109-3b3b-410e-a54d-9238f126b57b"
            }
          ]
        },
        {
          "id": "a6a21dcf-796d-40b8-80ac-7c89161a69f5",
          "name": "getPolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=GetPolicyVersion?PolicyArn=PolicyArn&VersionId=VersionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified version of the specified managed policy,\n      including the policy document."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e93cdf3d-0670-49b1-8314-412fcc942b14"
            }
          ]
        }
      ]
    },
    {
      "name": "Roles",
      "item": [
        {
          "id": "dcb21c97-d43e-432f-ad26-2001f16f5f9d",
          "name": "createRole",
          "request": {
            "url": "http://example.com/api/?Action=CreateRole?AssumeRolePolicyDocument=AssumeRolePolicyDocument&Path=Path&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new role for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cbcba7c6-a6b6-4216-b740-c23090805148"
            }
          ]
        },
        {
          "id": "d711a672-1d67-43c5-80ce-8bbe90a06409",
          "name": "deleteRole",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRole?RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e09ca5f0-c1f0-42b4-b8ed-8bc193a7d2fd"
            }
          ]
        },
        {
          "id": "c833a708-822b-498e-893f-4d1f37fb5ab6",
          "name": "getRole",
          "request": {
            "url": "http://example.com/api/?Action=GetRole?RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified role, including the role's path, GUID, ARN,\n      and the role's trust policy that grants permission to assume the role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4744ae20-0f26-4292-8b75-94dced3cfc30"
            }
          ]
        },
        {
          "id": "c55d6393-9c17-4dfc-a329-591e14534437",
          "name": "listRoles",
          "request": {
            "url": "http://example.com/api/?Action=ListRoles?Marker=Marker&MaxItems=MaxItems&PathPrefix=PathPrefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the IAM roles that have the specified path prefix."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bea49831-802e-4ade-b6d5-23cfd3a1d13c"
            }
          ]
        }
      ]
    },
    {
      "name": "SAML Providers",
      "item": [
        {
          "id": "0271f782-d229-4ae9-a34e-872e9c1f3de9",
          "name": "createSAMLProvider",
          "request": {
            "url": "http://example.com/api/?Action=CreateSAMLProvider?Name=Name&SAMLMetadataDocument=SAMLMetadataDocument",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an IAM resource that describes an identity provider (IdP) that supports SAML\n      2."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27d0ce91-3cde-4ebe-99fb-9f5764ba375b"
            }
          ]
        },
        {
          "id": "a7cfaec7-18d1-4619-9898-4e28bf0a7d9b",
          "name": "deleteSAMLProvider",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSAMLProvider?SAMLProviderArn=SAMLProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a SAML provider resource in IAM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3fc50f47-2cad-4bfd-b347-26c3db41252b"
            }
          ]
        },
        {
          "id": "bce5d4e3-cfb8-4d6d-956e-1762421dcde6",
          "name": "getSAMLProvider",
          "request": {
            "url": "http://example.com/api/?Action=GetSAMLProvider?SAMLProviderArn=SAMLProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the SAML provider metadocument that was uploaded when the IAM SAML provider\n      resource object was created or updated."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2e5e37e8-9329-4a4e-ab9b-61eada426787"
            }
          ]
        },
        {
          "id": "7d175031-4ad2-43d5-a5e3-fff5cb3c23ec",
          "name": "listSAMLProviders",
          "request": {
            "url": "http://example.com/api/?Action=ListSAMLProviders?SAMLProviderList.member.N=SAMLProviderList.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the SAML provider resource objects defined in IAM in the account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a11fb9f2-1014-43dc-b868-4a16f5f6e43d"
            }
          ]
        }
      ]
    },
    {
      "name": "Service Specific Credentials",
      "item": [
        {
          "id": "4a0d4985-4900-4a93-9cef-d76f469e308e",
          "name": "createServiceSpecificCredential",
          "request": {
            "url": "http://example.com/api/?Action=CreateServiceSpecificCredential?ServiceName=ServiceName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates a set of credentials consisting of a user name and password that can be used\n      to access the service specified in the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e46db67c-b847-4759-83ab-b911499e987a"
            }
          ]
        },
        {
          "id": "80c9262d-9344-4ff2-a257-5109647e5c1e",
          "name": "deleteServiceSpecificCredential",
          "request": {
            "url": "http://example.com/api/?Action=DeleteServiceSpecificCredential?ServiceSpecificCredentialId=ServiceSpecificCredentialId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified service-specific credential."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7170faa3-d497-4c13-a6ab-fef4ba0e0cd4"
            }
          ]
        },
        {
          "id": "252375dc-38ef-4f8a-aa59-759994d96f1b",
          "name": "listServiceSpecificCredentials",
          "request": {
            "url": "http://example.com/api/?Action=ListServiceSpecificCredentials?ServiceName=ServiceName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the service-specific credentials associated with the\n      specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "afd4d430-5723-4265-9f66-b722ed4c1846"
            }
          ]
        },
        {
          "id": "9ac8af7f-75b3-4ccb-ba6f-a79176cc6cde",
          "name": "resetServiceSpecificCredential",
          "request": {
            "url": "http://example.com/api/?Action=ResetServiceSpecificCredential?ServiceSpecificCredentialId=ServiceSpecificCredentialId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets the password for a service-specific credential."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9e97a88-899e-482f-b21e-595c20e11801"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "e7539394-4a91-4576-9718-3b2fe881bc15",
          "name": "createUser",
          "request": {
            "url": "http://example.com/api/?Action=CreateUser?Path=Path&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new IAM user for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77a0358b-2295-4b1b-bb64-61acfd1c29e8"
            }
          ]
        },
        {
          "id": "c025697c-a84c-4223-ac9c-76b3d1ef6f3c",
          "name": "deleteUser",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUser?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "467e58b0-2403-4185-a369-39fdade2da60"
            }
          ]
        },
        {
          "id": "0456c98c-96da-4bd8-abb4-9b636bb2b4d9",
          "name": "getUser",
          "request": {
            "url": "http://example.com/api/?Action=GetUser?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified IAM user, including the user's creation\n      date, path, unique ID, and ARN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "73fc93e3-f7a2-4c21-848f-42a71e08c720"
            }
          ]
        },
        {
          "id": "fe964749-7ff0-430a-88d6-dbe44cf7df77",
          "name": "listUsers",
          "request": {
            "url": "http://example.com/api/?Action=ListUsers?Marker=Marker&MaxItems=MaxItems&PathPrefix=PathPrefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the IAM users that have the specified path prefix."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cdc95ad4-4e81-4a2f-8974-4966c910e8a8"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual MFA Device",
      "item": [
        {
          "id": "1bb405c9-ecef-4b99-8961-6ed8a4d519a8",
          "name": "createVirtualMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=CreateVirtualMFADevice?Path=Path&VirtualMFADeviceName=VirtualMFADeviceName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new virtual MFA device for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8291ce15-55f1-4193-baab-07b97e17fe6e"
            }
          ]
        },
        {
          "id": "6fbbfacf-a52e-41bc-a9ab-c444e7bef66a",
          "name": "deactivateMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=DeactivateMFADevice?SerialNumber=SerialNumber&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deactivates the specified MFA device and removes it from association with the user name\n      for which it was originally enabled."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5d9c614a-022c-4168-a253-e0557293a728"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Password Policies",
      "item": [
        {
          "id": "5a81e54e-42f8-45d9-8864-3faf86700edc",
          "name": "deleteAccountPasswordPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAccountPasswordPolicy?LimitExceeded=LimitExceeded&NoSuchEntity=NoSuchEntity&ServiceFailure=ServiceFailure",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the password policy for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "16e45315-139f-4fc2-8c47-09ed0e80b1fc"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Certificates",
      "item": [
        {
          "id": "a3657113-6db5-4872-9fdf-cd339074e48e",
          "name": "deleteServerCertificate",
          "request": {
            "url": "http://example.com/api/?Action=DeleteServerCertificate?ServerCertificateName=ServerCertificateName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified server certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8133a0e-723d-43d8-b4a4-fe1ce6cd19b1"
            }
          ]
        },
        {
          "id": "c113d4f3-685b-47ad-b94f-ef10476932ec",
          "name": "getServerCertificate",
          "request": {
            "url": "http://example.com/api/?Action=GetServerCertificate?ServerCertificateName=ServerCertificateName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified server certificate stored in IAM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e28edf7c-4289-4d61-b826-17985d364c74"
            }
          ]
        }
      ]
    },
    {
      "name": "Signing Certificates",
      "item": [
        {
          "id": "4cb8ac1a-9a30-4707-8dc6-810737c37ef9",
          "name": "deleteSigningCertificate",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSigningCertificate?CertificateId=CertificateId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a signing certificate associated with the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d6efd02f-e531-4db6-b380-f027605d88a7"
            }
          ]
        },
        {
          "id": "9c9adec1-01de-4c38-823d-2502798c34ea",
          "name": "listSigningCertificates",
          "request": {
            "url": "http://example.com/api/?Action=ListSigningCertificates?Marker=Marker&MaxItems=MaxItems&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the signing certificates associated with the specified IAM\n      user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3028eafe-97b6-4bc1-9780-9b902c243589"
            }
          ]
        }
      ]
    },
    {
      "name": "SSH Public Key",
      "item": [
        {
          "id": "a1a384c0-b496-4a32-b832-12e2efe954a7",
          "name": "deleteSSHPublicKey",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSSHPublicKey?SSHPublicKeyId=SSHPublicKeyId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified SSH public key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "47da0a5a-04c1-4e63-b5d2-7a7a723f51bb"
            }
          ]
        },
        {
          "id": "e788c229-4e55-4839-b80a-b0c200b2085a",
          "name": "getSSHPublicKey",
          "request": {
            "url": "http://example.com/api/?Action=GetSSHPublicKey?Encoding=Encoding&SSHPublicKeyId=SSHPublicKeyId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the specified SSH public key, including metadata about the key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2cdac6ca-7632-4d4b-8446-9c2a48e3dc79"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual MFA Devices",
      "item": [
        {
          "id": "ecf3bfb5-d4ca-4703-aae7-10ee885cf153",
          "name": "deleteVirtualMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=DeleteVirtualMFADevice?SerialNumber=SerialNumber",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a virtual MFA device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "828b322c-2f6e-4871-9c7c-8118ac1d88d0"
            }
          ]
        },
        {
          "id": "e194ccda-508a-4c86-8264-84854f5e70c6",
          "name": "listVirtualMFADevices",
          "request": {
            "url": "http://example.com/api/?Action=ListVirtualMFADevices?AssignmentStatus=AssignmentStatus&Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the virtual MFA devices defined in the AWS account by assignment status."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e068e14e-15a4-4c44-af63-8185574bde61"
            }
          ]
        }
      ]
    },
    {
      "name": "MFA Devices",
      "item": [
        {
          "id": "3a7f717a-219b-4d24-9f82-baf5ecb1437a",
          "name": "enableMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=EnableMFADevice?AuthenticationCode1=AuthenticationCode1&AuthenticationCode2=AuthenticationCode2&SerialNumber=SerialNumber&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables the specified MFA device and associates it with the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ec1ee0f4-8db5-49cf-bb91-7f1e02afed7f"
            }
          ]
        },
        {
          "id": "e395fe15-e673-47fa-83eb-56064087b435",
          "name": "listMFADevices",
          "request": {
            "url": "http://example.com/api/?Action=ListMFADevices?Marker=Marker&MaxItems=MaxItems&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the MFA devices for an IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d9cc6299-ac30-43af-b31e-6a02a8586d78"
            }
          ]
        },
        {
          "id": "b1e1b7c3-8a2c-4752-b555-0a9fe835f21a",
          "name": "resyncMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=ResyncMFADevice?AuthenticationCode1=AuthenticationCode1&AuthenticationCode2=AuthenticationCode2&SerialNumber=SerialNumber&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Synchronizes the specified MFA device with its IAM resource object on the AWS\n      servers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f55a36f-282c-47ca-9bed-b2189732a165"
            }
          ]
        }
      ]
    },
    {
      "name": "Credential Reports",
      "item": [
        {
          "id": "64a0133a-6a89-4b1b-8437-a1d762640c63",
          "name": "generateCredentialReport",
          "request": {
            "url": "http://example.com/api/?Action=GenerateCredentialReport?Description=Description&State=State",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates a credential report for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4555053f-0b68-4c8b-9022-328f54c6a244"
            }
          ]
        },
        {
          "id": "b7f29a31-d685-404b-9c8e-7223572fc97b",
          "name": "getCredentialReport",
          "request": {
            "url": "http://example.com/api/?Action=GetCredentialReport?Content=Content&GeneratedTime=GeneratedTime&ReportFormat=ReportFormat",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a credential report for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4cb4a4b1-815f-4c12-b38f-314e92097392"
            }
          ]
        }
      ]
    },
    {
      "name": "Accounts",
      "item": [
        {
          "id": "e45fa45f-b35f-47d6-b1e8-8d79be305dc3",
          "name": "getAccountAuthorizationDetails",
          "request": {
            "url": "http://example.com/api/?Action=GetAccountAuthorizationDetails?Filter.member.N=Filter.member.N&Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about all IAM users, groups, roles, and policies in your AWS\n      account, including their relationships to one another."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "21081c02-2bfd-4e26-8fc4-1f100d9e8ea6"
            }
          ]
        },
        {
          "id": "69d36a65-eb25-48b4-a32c-fb3b9073d7ca",
          "name": "getAccountPasswordPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetAccountPasswordPolicy?PasswordPolicy=PasswordPolicy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the password policy for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9971d34d-2f4e-4403-abe2-7c3d287127d3"
            }
          ]
        },
        {
          "id": "4a5cb6e0-c95b-4e79-8af2-93812547a67b",
          "name": "getAccountSummary",
          "request": {
            "url": "http://example.com/api/?Action=GetAccountSummary?SummaryMap\n            , SummaryMap.entry.N.key (key), SummaryMapentry.N.value (value)=SummaryMap%0A%20%20%20%20%20%20%20%20%20%20%20%20%2C%20SummaryMap.entry.N.key%20%28key%29%2C%20SummaryMapentry.N.value%20%28value%29",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about IAM entity usage and IAM quotas in the AWS\n      account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "44254dfd-5fe3-47a4-b544-42dbd69f04c7"
            }
          ]
        }
      ]
    },
    {
      "name": "Context Keys For Custom Policies",
      "item": [
        {
          "id": "8b01710b-1071-4c7b-a857-61534fc5c525",
          "name": "getContextKeysForCustomPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetContextKeysForCustomPolicy?PolicyInputList.member.N=PolicyInputList.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of all of the context keys referenced in the input policies."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eddfbb11-17c4-409d-9742-62a96e0b17ec"
            }
          ]
        }
      ]
    },
    {
      "name": "Context Keys For Principal Policies",
      "item": [
        {
          "id": "64ff75f7-6867-4449-a27b-6f0aae7919e1",
          "name": "getContextKeysForPrincipalPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetContextKeysForPrincipalPolicy?PolicyInputList.member.N=PolicyInputList.member.N&PolicySourceArn=PolicySourceArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of all of the context keys referenced in all of the IAM policies attached\n      to the specified IAM entity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0fd6c737-1623-41b8-bfaf-95aea7c3eaca"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Aliases",
      "item": [
        {
          "id": "27f00c6f-6d80-45bf-ac52-eed9b004768d",
          "name": "listAccountAliases",
          "request": {
            "url": "http://example.com/api/?Action=ListAccountAliases?Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the account alias associated with the AWS account (Note: you can have only\n      one)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "715f414d-d24a-4d27-9bba-3ac1932015c2"
            }
          ]
        }
      ]
    },
    {
      "name": "Attached Group Polic