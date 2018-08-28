{
  "info": {
    "name": "AWS Identity and Access Management API Update Assume Role Policy",
    "_postman_id": "9d6657b8-6632-4f55-82de-7d578f29f30b",
    "description": "Updates the policy that grants an IAM entity permission to assume a role.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "OpenID Connect Providers",
      "item": [
        {
          "id": "28c7e82c-cf31-4a7e-8047-7e7ffa3d2d7f",
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
              "id": "23c3ce85-11ba-45b9-bb37-90d952492164"
            }
          ]
        },
        {
          "id": "b26ba48b-3c49-4eb9-9dc6-e9453b1db96f",
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
              "id": "3771caa1-c0ca-472f-802f-c0eeb6fd0515"
            }
          ]
        },
        {
          "id": "1aee63ca-fb6b-423d-9439-5176a3bbb4d4",
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
              "id": "298f541f-10ca-40e9-9c55-2029a6bcb7a7"
            }
          ]
        },
        {
          "id": "a7e4a8fb-ba1f-4d02-a078-c61b840ae37f",
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
              "id": "1e47fe69-6b16-4301-a804-c7f6a83b2c0e"
            }
          ]
        },
        {
          "id": "e95b827e-f6a3-4a41-849a-e6d79681ced5",
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
              "id": "9e75eec4-b555-4f06-adfc-0c8d2bff5eef"
            }
          ]
        },
        {
          "id": "263657ff-6ed1-4285-b3e1-4fd2543f9367",
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
              "id": "913e158c-de50-4b93-ac11-5e725813ccf6"
            }
          ]
        }
      ]
    },
    {
      "name": "Role Instance",
      "item": [
        {
          "id": "5378f06a-a9af-46b3-abe8-1894fb87d918",
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
              "id": "ed769be9-d315-4703-9493-660a16c32031"
            }
          ]
        }
      ]
    },
    {
      "name": "User Groups",
      "item": [
        {
          "id": "d136b3d5-003a-4df9-8239-c63ed164734d",
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
              "id": "fcc5b385-1175-4059-81a3-884d45714a30"
            }
          ]
        }
      ]
    },
    {
      "name": "Group Policies",
      "item": [
        {
          "id": "939474ec-729d-4e81-9b30-6d190fafba15",
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
              "id": "982f467b-c293-494d-9370-700e95c6a2f1"
            }
          ]
        },
        {
          "id": "c843fc63-3373-4a0b-895d-9ac35ffa6ea8",
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
              "id": "4eba458a-c283-4a89-9623-8f07917d8652"
            }
          ]
        },
        {
          "id": "eacc1beb-eaf4-44e7-8f5c-9a585872795b",
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
              "id": "85c40981-4539-4655-b307-230b5914618b"
            }
          ]
        },
        {
          "id": "452d7a2a-ef06-47db-829c-b29edbdf607f",
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
              "id": "ce5ccdc6-d5e8-40bd-9ca9-f1b108433dd5"
            }
          ]
        },
        {
          "id": "20040318-a570-45de-a1a1-52d4c2d28a27",
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
              "id": "48b9e7c9-239b-4ecd-9795-61fad6b4dbdf"
            }
          ]
        },
        {
          "id": "02665f43-e71a-4fd8-b540-2e84adaefaa4",
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
              "id": "8463539b-9ad1-4b93-9918-dd56dd8f7a74"
            }
          ]
        }
      ]
    },
    {
      "name": "Role Policies",
      "item": [
        {
          "id": "10608952-19b1-48e2-933d-4f6baec6082f",
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
              "id": "d06bda53-6d0e-4961-862e-9fa1c4a3e49f"
            }
          ]
        },
        {
          "id": "af5a55c6-c30d-4b46-ac03-975f09572232",
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
              "id": "23b1068c-9b31-4d19-9972-963ac6c177bc"
            }
          ]
        },
        {
          "id": "3d9c8aa8-3752-4a73-a13b-b23b29dc28b9",
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
              "id": "cf6e067e-a051-45b5-9037-7e6282d08759"
            }
          ]
        },
        {
          "id": "8a8c1d12-f3f3-414e-9500-d1969e0c316e",
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
              "id": "97935421-1f6b-40fe-8ccf-fffe8fa03de7"
            }
          ]
        },
        {
          "id": "38e14a3a-af74-4b86-8420-4076a57acbb5",
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
              "id": "4bcb4b34-eaaa-4cf8-91e6-0d49a1755034"
            }
          ]
        },
        {
          "id": "36206139-2ac4-47d7-b2b4-08da2410b1d6",
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
              "id": "cc1265fb-09a1-4d4b-8f3f-7a3adf9cfdae"
            }
          ]
        }
      ]
    },
    {
      "name": "User Policies",
      "item": [
        {
          "id": "e4915055-5a36-4057-b619-36ac485d82b0",
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
              "id": "779614ac-8063-4358-9167-a9018d87aedc"
            }
          ]
        },
        {
          "id": "c70ba0bd-2044-41c2-9e2a-d7b7b72ba979",
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
              "id": "d386dfcc-0f46-41f4-889e-e4d3f616772d"
            }
          ]
        },
        {
          "id": "afe05a87-de93-4568-a3cb-2e51829169c0",
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
              "id": "de1e336b-2a5e-4db0-a51b-40068b154ad5"
            }
          ]
        },
        {
          "id": "95f0c600-aab6-448b-846e-d97b04cc8843",
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
              "id": "7c12a6c0-8b37-4dc2-80b4-bf92900cc743"
            }
          ]
        },
        {
          "id": "b0653995-9398-40d1-8a93-08ab665b5439",
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
              "id": "525a41a9-bb10-4ccd-962e-041d1db00800"
            }
          ]
        }
      ]
    },
    {
      "name": "Passwords",
      "item": [
        {
          "id": "9810b944-dc74-42e2-9a03-a5fdab5e4f7e",
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
              "id": "3a338c95-cf64-44de-bfd5-d04a0c793dac"
            }
          ]
        }
      ]
    },
    {
      "name": "Access Keys",
      "item": [
        {
          "id": "1057a7e9-6e12-47aa-a99d-6d46299c910a",
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
              "id": "6dba7cf6-aaff-41b8-9740-cc5c3b71d69a"
            }
          ]
        },
        {
          "id": "5f153738-8f45-4579-a20f-0feab2794ff3",
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
              "id": "9f225da6-c6b1-4139-b4de-c6fa504c8d5d"
            }
          ]
        },
        {
          "id": "6dbfe278-8f69-4446-ac11-759791b0b7c2",
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
              "id": "1977726e-2966-4c0e-9c4b-9697b6aadebc"
            }
          ]
        },
        {
          "id": "f083f65c-78f0-44d6-9e1e-b53d82dd1542",
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
              "id": "832461db-4e54-4bd7-abcc-f3b86a0f1c53"
            }
          ]
        },
        {
          "id": "44b58631-d752-4a67-9eb3-e4c2105077de",
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
              "id": "21242405-15af-4628-bd34-fa5e310fb095"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Alias",
      "item": [
        {
          "id": "d1ea5b02-31f8-4804-bae1-9da8f8dbf3fd",
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
              "id": "0c397ee7-fc85-4c4f-9356-b89bbfc72158"
            }
          ]
        },
        {
          "id": "fdda55af-1645-4fbe-bf6e-5f31c5ba616f",
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
              "id": "f423783e-4cc0-4fe3-8c01-d2e3742bba72"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "2c9bb35b-7ab2-4d00-8b16-85264f3ed98e",
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
              "id": "4ae3773b-3049-4b1a-b3e4-844d9c70c500"
            }
          ]
        },
        {
          "id": "cd808a08-d193-44d1-a4f8-ea7492ef880a",
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
              "id": "943db721-2d43-42f2-b073-e5f950d3acd2"
            }
          ]
        },
        {
          "id": "77d3ba17-4108-4aa7-8689-9484b683b813",
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
              "id": "aecec8bd-ee0f-4b02-a219-da110ec83c8d"
            }
          ]
        },
        {
          "id": "48d5b8c5-9ccd-4b62-abce-be40f1c14c1f",
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
              "id": "9f33e19f-6698-4c14-b39d-875bcafca060"
            }
          ]
        }
      ]
    },
    {
      "name": "Instance Profiles",
      "item": [
        {
          "id": "783db3db-a136-4df5-ba88-1043776ddc68",
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
              "id": "47051dfd-bcc2-4185-9626-14ed1f1b0e99"
            }
          ]
        },
        {
          "id": "6fcb157d-fe33-4c39-a94d-b32fae6e9de7",
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
              "id": "3baf867a-904c-403f-a119-5c67de12bb5a"
            }
          ]
        },
        {
          "id": "63fe6b32-5ee1-48be-815e-c3dec410aff5",
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
              "id": "6e63c0f9-4f65-4b7b-9917-721a518f2c7d"
            }
          ]
        },
        {
          "id": "13cbe49d-cde0-4df5-9ca6-14051d98a290",
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
              "id": "7833f77b-6721-4187-9b9b-cfe258d2c8e0"
            }
          ]
        }
      ]
    },
    {
      "name": "Login Profiles",
      "item": [
        {
          "id": "e55593a6-16ad-4583-b4ab-e96afef4fe3b",
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
              "id": "f5cfdff1-8915-4dca-96dd-c57f745a5942"
            }
          ]
        },
        {
          "id": "7af7effb-58ec-4424-9912-f5d990bcb7af",
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
              "id": "3df4368e-79bc-4ac0-9832-3da29bd47a99"
            }
          ]
        },
        {
          "id": "ebfd6727-2344-44d7-8dce-fa2abff2c766",
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
              "id": "eb1c58b3-7ea6-451f-8d5d-85d295a48867"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "2bb391a2-4055-4f50-9eae-c8c1fe5026cf",
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
              "id": "c67bd937-9dd4-4006-bdd2-8c1ba83d702c"
            }
          ]
        },
        {
          "id": "cfd0fa99-5fdf-4d84-8fb5-0ad3b9f9b2ed",
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
              "id": "273f4fff-6796-443b-80e2-9e205a0b4005"
            }
          ]
        },
        {
          "id": "a87ec3a8-fd0a-4d02-81a2-7e11f6f805b9",
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
              "id": "efe26347-67e1-4114-8bb4-52c7fad0f1bd"
            }
          ]
        },
        {
          "id": "b04e4498-1d89-4389-a799-7b7eca4b5e5b",
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
              "id": "c7641516-1704-49c8-9289-2bcb1f4a4d67"
            }
          ]
        },
        {
          "id": "b888f42a-ae3f-42ce-b553-0496f57dfd25",
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
              "id": "9c1a0980-aff6-4aaa-8ff4-dfdfe8aff78e"
            }
          ]
        },
        {
          "id": "13f56843-de11-4c42-ad7f-dc96b4d96ad1",
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
              "id": "f3c19422-23d3-4bf8-9bc8-e820e4a96993"
            }
          ]
        }
      ]
    },
    {
      "name": "Roles",
      "item": [
        {
          "id": "966fdd41-31d4-48c3-984d-2cdae149b8cc",
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
              "id": "7c2f096e-5131-4c93-b695-f6418a0709b7"
            }
          ]
        },
        {
          "id": "8459544d-f08b-44e7-b841-232a65b6820e",
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
              "id": "0210c135-cb72-49df-9e3e-2d2894d83026"
            }
          ]
        },
        {
          "id": "c583f349-7810-4786-b2e0-670e8680d1ec",
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
              "id": "98acf687-f5b8-40c0-869a-04b68137fa94"
            }
          ]
        },
        {
          "id": "3256c92c-6f27-4cd4-b497-ca1f20934a14",
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
              "id": "f5eef910-8af8-4b50-b91f-e3524474359a"
            }
          ]
        }
      ]
    },
    {
      "name": "SAML Providers",
      "item": [
        {
          "id": "a8337dbf-3d85-4d68-a851-edf2385c72f7",
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
              "id": "1ce58cd1-35d6-4711-9ed4-49bf3c382583"
            }
          ]
        },
        {
          "id": "897d74d3-56fc-4d4b-91eb-dbd93db4c321",
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
              "id": "f05296c1-0aa6-4ab9-88d5-925ef8fdbcb1"
            }
          ]
        },
        {
          "id": "72fa901e-f00a-4608-91d8-4461d446bb6f",
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
              "id": "d9626254-3317-4361-bd4f-b6a60399349f"
            }
          ]
        },
        {
          "id": "1f135648-ae1c-43cd-bf44-1d2e4d2323ca",
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
              "id": "349d9e00-dae4-41e1-ab06-cac98bd168a8"
            }
          ]
        }
      ]
    },
    {
      "name": "Service Specific Credentials",
      "item": [
        {
          "id": "378a9826-a625-4c29-a71d-b9a4d38a9418",
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
              "id": "f9efe070-b36b-441b-aab4-46c1ea5393b5"
            }
          ]
        },
        {
          "id": "d7301f64-59b6-4732-a1c8-4e2c03f0f489",
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
              "id": "3d9dd33b-d872-4cfc-a4b3-375939f368e7"
            }
          ]
        },
        {
          "id": "c43af270-5ac9-41b0-bd99-aaa66b421177",
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
              "id": "df77be6f-206b-4af1-be9b-86b7c2772b1a"
            }
          ]
        },
        {
          "id": "261bf1a6-ddb1-4dff-8d86-ed1238fa9dd8",
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
              "id": "f762849d-7c33-4652-a5fe-2d7768c5e36b"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "5972b1c9-211d-4145-9d74-2d8ed12aa8e9",
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
              "id": "60e55bde-aefa-42a4-b2ec-760383b4229f"
            }
          ]
        },
        {
          "id": "ca4c9d99-b67c-49a1-ae0f-c82abb88d935",
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
              "id": "5668e57c-3d8f-4c42-bd34-9ad70c2b8656"
            }
          ]
        },
        {
          "id": "f82127e5-bf64-4783-9c5f-b04520859c87",
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
              "id": "bf34beca-6dd6-457e-8b2c-0d580a0750ce"
            }
          ]
        },
        {
          "id": "b0aef79e-1b66-4981-aec0-91ce74e1f01e",
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
              "id": "6161018e-643f-4ae9-850e-dd91ac662581"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual MFA Device",
      "item": [
        {
          "id": "64fec627-2e6a-45ab-a83f-d28f56b8c03c",
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
              "id": "4defde19-3ae2-42a8-a36c-6427a2a62173"
            }
          ]
        },
        {
          "id": "95a82b31-192a-474d-820d-2c0334470ef1",
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
              "id": "b1b4333d-d3f4-4f3c-8290-fc1304802e9b"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Password Policies",
      "item": [
        {
          "id": "344c2492-9be1-427b-a801-74fca242e838",
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
              "id": "2598b2b0-6cbb-4363-9ef1-d36654218dc6"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Certificates",
      "item": [
        {
          "id": "941aa57c-ea8e-46f0-bc4f-7b7dfc009683",
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
              "id": "20d70bc4-369e-494b-9993-cbfe6fe0256f"
            }
          ]
        },
        {
          "id": "a8efb3ae-f832-45a0-b29d-4a609a091fcf",
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
              "id": "f5c9cdcb-5f8f-438a-bd48-7fe0a009eabc"
            }
          ]
        }
      ]
    },
    {
      "name": "Signing Certificates",
      "item": [
        {
          "id": "0ce59a88-24b2-41a7-95a0-8264cf709469",
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
              "id": "00159ae0-43c3-43ba-bae1-c9cf42d140f1"
            }
          ]
        },
        {
          "id": "08e77fb2-d330-4a25-b734-a3887cde6848",
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
              "id": "96910d08-46ec-4134-9175-5260c29a1677"
            }
          ]
        }
      ]
    },
    {
      "name": "SSH Public Key",
      "item": [
        {
          "id": "a0fb03b4-baba-4258-8ecd-7aa1f91fc0ff",
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
              "id": "d5a08c8f-493b-416e-9a7b-31645a7d374b"
            }
          ]
        },
        {
          "id": "c3004b55-876d-42ed-94aa-1a9aebdb79b8",
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
              "id": "56e3313b-8dda-42c4-84dd-42f8add8b6dd"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual MFA Devices",
      "item": [
        {
          "id": "3fbeab19-1348-4929-87bc-d089dedc0180",
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
              "id": "76295143-9b6d-45b9-979d-f59121e21b23"
            }
          ]
        },
        {
          "id": "48e6ccab-18c7-4d6b-90e0-81199603d046",
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
              "id": "5ef18ab0-4a5b-4ef3-aeb8-50cbe0f57767"
            }
          ]
        }
      ]
    },
    {
      "name": "MFA Devices",
      "item": [
        {
          "id": "072aa69c-0aa9-4411-a0d6-476651f1f172",
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
              "id": "e7ccfa6d-af21-4638-8ce2-d578572362d4"
            }
          ]
        },
        {
          "id": "6d4ab6f4-0d80-4755-bc37-f1106290381c",
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
              "id": "98a3f17e-d1f8-4d17-a9b2-41867bc18625"
            }
          ]
        },
        {
          "id": "140f751d-d42e-41c9-87d3-455e848e461f",
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
              "id": "74809866-a241-4ebb-8946-5f75efbb0551"
            }
          ]
        }
      ]
    },
    {
      "name": "Credential Reports",
      "item": [
        {
          "id": "22df381f-742c-4b83-b13d-ba63d504ab86",
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
              "id": "9c120eb5-e423-49fb-b32e-3c57b2da2815"
            }
          ]
        },
        {
          "id": "2f9b33ee-5e11-4d2f-b323-6d477b3a41a8",
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
              "id": "17ab8956-f687-4c04-b723-ff0274245684"
            }
          ]
        }
      ]
    },
    {
      "name": "Accounts",
      "item": [
        {
          "id": "f60b13be-40fd-40bc-90a6-f2a8fe9dbb0d",
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
              "id": "3b1eb1f0-4663-46ed-bc6c-6c959c191514"
            }
          ]
        },
        {
          "id": "1bc07ae0-e288-483a-9d36-250f3189483b",
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
              "id": "9cd5ec6b-b1d9-4727-a620-c941b64b862d"
            }
          ]
        },
        {
          "id": "d534317e-f2bf-43fc-afa9-53fa2f7a59b9",
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
              "id": "025ef079-8eb3-4149-a39f-e547c3a465a9"
            }
          ]
        }
      ]
    },
    {
      "name": "Context Keys For Custom Policies",
      "item": [
        {
          "id": "042593aa-cd16-4f30-add5-8eb40999c85d",
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
              "id": "8e3b753e-6579-4a8d-9dbb-d65d95a82b3f"
            }
          ]
        }
      ]
    },
    {
      "name": "Context Keys For Principal Policies",
      "item": [
        {
          "id": "02d72b74-85d7-4a17-b000-de32e2c6213e",
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
              "id": "95f5bedd-e480-4c3d-b142-6ab90c58f544"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Aliases",
      "item": [
        {
          "id": "cede749d-7afe-4345-8718-02547576a91a",
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
              "id": "2f23c696-c035-4ffe-8a8a-b0b08c39d4d1"
            }
          ]
        }
      ]
    },
    {
      "name": "Attached 