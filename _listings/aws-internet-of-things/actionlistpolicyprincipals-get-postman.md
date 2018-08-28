{
  "info": {
    "name": "AWS Internet of Things API List Policy Principals",
    "_postman_id": "94eb46ac-4fe4-448f-8ec0-9a7e3db138ea",
    "description": "Lists the principals associated with the specified policy.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Certificate Transfers",
      "item": [
        {
          "id": "9d660486-f7a9-4ded-8a39-7c503cbb8b7e",
          "name": "acceptCertificateTransfer",
          "request": {
            "url": "http://example.com/api/?Action=AcceptCertificateTransfer?certificateId=certificateId&setAsActive=setAsActive",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Accepts a pending certificate transfer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e4cc890-0ec1-47ed-8e0d-c2fd407fa681"
            }
          ]
        },
        {
          "id": "d99d46e1-e058-4ed6-a076-bdd4485b4ee1",
          "name": "cancelCertificateTransfer",
          "request": {
            "url": "http://example.com/api/?Action=CancelCertificateTransfer?certificateId=certificateId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels a pending transfer for the specified certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc04eae8-ff5e-4b91-8bfa-97c2287b7546"
            }
          ]
        }
      ]
    },
    {
      "name": "Principal Policies",
      "item": [
        {
          "id": "5a3031c3-0a11-4a27-915a-41d7e0075a3a",
          "name": "attachPrincipalPolicy",
          "request": {
            "url": "http://example.com/api/?Action=AttachPrincipalPolicy?policyName=policyName&principal=principal",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified policy to the specified principal (certificate or other credential)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f4fa3e7e-8317-46e9-af88-1fd3f8d1b643"
            }
          ]
        },
        {
          "id": "abd6434d-d53c-4d67-8e67-48c56dd4a7c4",
          "name": "detachPrincipalPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DetachPrincipalPolicy?policyName=policyName&principal=principal",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified policy from the specified certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b015ac98-23cf-4562-bf35-a34202864adb"
            }
          ]
        }
      ]
    },
    {
      "name": "Thing Principals",
      "item": [
        {
          "id": "6d0de98a-aaf8-4fe4-83cb-26b548a00235",
          "name": "attachThingPrincipal",
          "request": {
            "url": "http://example.com/api/?Action=AttachThingPrincipal?principal=principal&thingName=thingName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified principal to the specified thing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "74ad9a6a-15d0-490b-935c-3b58ee612d32"
            }
          ]
        },
        {
          "id": "049b3f56-7b17-41d7-bb8b-c52cfe66e6bb",
          "name": "detachThingPrincipal",
          "request": {
            "url": "http://example.com/api/?Action=DetachThingPrincipal?principal=principal&thingName=thingName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches the specified principal from the specified thing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31b5e8c2-866d-4a7f-96b3-6427a999cf00"
            }
          ]
        }
      ]
    },
    {
      "name": "Certificates",
      "item": [
        {
          "id": "c244f20d-7a3c-412d-a626-b8d0d4af7b40",
          "name": "createCertificateFromCsr",
          "request": {
            "url": "http://example.com/api/?Action=CreateCertificateFromCsr?certificateSigningRequest=certificateSigningRequest&setAsActive=setAsActive",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an X."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6c95a9a-3fe3-4dde-bbb2-075ea16ea1d5"
            }
          ]
        },
        {
          "id": "3921101e-fb0e-4316-b3f6-aa3e00d0f1bb",
          "name": "deleteCertificate",
          "request": {
            "url": "http://example.com/api/?Action=DeleteCertificate?certificateId=certificateId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ee480860-aa36-4f05-922a-877053e87816"
            }
          ]
        },
        {
          "id": "f33a5944-cd22-43ac-82a5-093cd7a6ecae",
          "name": "describeCertificate",
          "request": {
            "url": "http://example.com/api/?Action=DescribeCertificate?certificateId=certificateId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the specified certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d4c176c-6d3c-4b09-96b9-0550b0f1ece5"
            }
          ]
        },
        {
          "id": "b9b549e9-3bd2-44ed-99e6-c69acda7a477",
          "name": "listCertificates",
          "request": {
            "url": "http://example.com/api/?Action=ListCertificates?ascendingOrder=ascendingOrder&marker=marker&pageSize=pageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the certificates registered in your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f2483435-cd5d-4650-a2f9-729d65c285c8"
            }
          ]
        },
        {
          "id": "74ebcdfd-9674-4b8c-9f2a-1271afc6b842",
          "name": "listOutgoingCertificates",
          "request": {
            "url": "http://example.com/api/?Action=ListOutgoingCertificates?ascendingOrder=ascendingOrder&marker=marker&pageSize=pageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists certificates that are being transfered but not yet accepted."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c698dfc2-2f58-4a74-b8be-db1ab210e3a3"
            }
          ]
        }
      ]
    },
    {
      "name": "Keys And Certificates",
      "item": [
        {
          "id": "041e9928-ebb8-4607-a702-2b8d60368413",
          "name": "createKeysAndCertificate",
          "request": {
            "url": "http://example.com/api/?Action=CreateKeysAndCertificate?setAsActive=setAsActive",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a 2048-bit RSA key pair and issues an X."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "37e8349b-f782-4b5e-ac49-b3f59ec78f40"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "b1485419-5830-46ea-a744-79953ee81e91",
          "name": "createPolicy",
          "request": {
            "url": "http://example.com/api/?Action=CreatePolicy?policyDocument=policyDocument&policyName=policyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an AWS IoT policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "73cbe96a-2ab2-422c-b346-78e17460a97a"
            }
          ]
        },
        {
          "id": "86016dc4-cf5f-4f42-b59a-c35651a0ec7f",
          "name": "createPolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=CreatePolicyVersion?policyDocument=policyDocument&policyName=policyName&setAsDefault=setAsDefault",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new version of the specified AWS IoT policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fae4f893-1310-4f99-820f-e78485e7d4d5"
            }
          ]
        },
        {
          "id": "04cbf249-74a5-4512-8720-de3a808687c9",
          "name": "deletePolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeletePolicy?policyName=policyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d3c7d1c-38b3-47f1-8c94-b7ad9c4c7737"
            }
          ]
        },
        {
          "id": "4f84ff3e-5bd2-439f-99fb-74143db13d95",
          "name": "deletePolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=DeletePolicyVersion?policyName=policyName&policyVersionId=policyVersionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified version of the specified policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ed29aa3-db2f-4687-8a83-a048f16d0976"
            }
          ]
        },
        {
          "id": "2c303319-0a48-4f55-ba73-04fc846fd6c8",
          "name": "getPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetPolicy?policyName=policyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the specified policy with the policy document of the default version."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b524c1b-e6c6-43bc-b244-62f71148d4ab"
            }
          ]
        },
        {
          "id": "04908091-2ccd-44ef-a5c7-b3f31be69ebb",
          "name": "getPolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=GetPolicyVersion?policyName=policyName&policyVersionId=policyVersionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the specified policy version."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ccf4813f-c4ac-4b9c-a26e-674e086309f7"
            }
          ]
        },
        {
          "id": "9e4109f1-63b6-44ed-84d4-05876bdafaa4",
          "name": "listPolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListPolicies?ascendingOrder=ascendingOrder&marker=marker&pageSize=pageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists your policies."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bbca2c06-2015-4bc7-9a3f-c384dc245a50"
            }
          ]
        }
      ]
    },
    {
      "name": "Things",
      "item": [
        {
          "id": "cefd831d-7ec2-41ed-baab-5c91d62f89fd",
          "name": "createThing",
          "request": {
            "url": "http://example.com/api/?Action=CreateThing?attributePayload=attributePayload&thingName=thingName&thingTypeName=thingTypeName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a thing record in the thing registry."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eae6ac16-a0d7-4963-8bd4-6a0cbeb48cc3"
            }
          ]
        },
        {
          "id": "3d5021f8-89c1-4f57-a5f9-74b80275a425",
          "name": "deleteThing",
          "request": {
            "url": "http://example.com/api/?Action=DeleteThing?expectedVersion=expectedVersion&thingName=thingName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified thing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3448fc75-b811-44b0-b798-243526b97276"
            }
          ]
        },
        {
          "id": "871caa58-a9fb-4bdb-8eca-21a4e65094b2",
          "name": "describeThing",
          "request": {
            "url": "http://example.com/api/?Action=DescribeThing?thingName=thingName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the specified thing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a1c5dfcc-62a7-4222-975e-6ffe36581d3d"
            }
          ]
        }
      ]
    },
    {
      "name": "Thing Types",
      "item": [
        {
          "id": "b53b4453-7a1a-452d-a09f-f16ec4fa1df8",
          "name": "createThingType",
          "request": {
            "url": "http://example.com/api/?Action=CreateThingType?thingTypeName=thingTypeName&thingTypeProperties=thingTypeProperties",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new thing type."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f967bb68-5ce2-47b4-81e7-85ca775553e5"
            }
          ]
        },
        {
          "id": "74c561f2-6818-4b73-98fb-d815c8b33f2d",
          "name": "deleteThingType",
          "request": {
            "url": "http://example.com/api/?Action=DeleteThingType?thingTypeName=thingTypeName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified thing type."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "334ac029-02e4-4bca-8041-24c6166fb073"
            }
          ]
        },
        {
          "id": "a7cb5882-2948-40c6-9379-94563f17427e",
          "name": "deprecateThingType",
          "request": {
            "url": "http://example.com/api/?Action=DeprecateThingType?thingTypeName=thingTypeName&undoDeprecate=undoDeprecate",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deprecates a thing type."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef472258-ffce-4cba-bfd4-3b42df70e1c0"
            }
          ]
        },
        {
          "id": "6b8a02c9-b933-492f-8377-8f6b21e4f22d",
          "name": "describeThingType",
          "request": {
            "url": "http://example.com/api/?Action=DescribeThingType?thingTypeName=thingTypeName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the specified thing type."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "621dd018-98b1-41dd-848a-009f9ba8c96d"
            }
          ]
        }
      ]
    },
    {
      "name": "Topic Rules",
      "item": [
        {
          "id": "d517cda7-4c7c-4f92-8c57-742626e78c9b",
          "name": "createTopicRule",
          "request": {
            "url": "http://example.com/api/?Action=CreateTopicRule?ruleName=ruleName&topicRulePayload=topicRulePayload",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77fcee58-b891-4a5a-bdcb-26ca4c414db6"
            }
          ]
        },
        {
          "id": "f28a18dc-90c6-49db-90df-02fb4a3c21b0",
          "name": "deleteTopicRule",
          "request": {
            "url": "http://example.com/api/?Action=DeleteTopicRule?ruleName=ruleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bce8f1bc-15bd-47b2-a7ab-a7bf66bf0954"
            }
          ]
        },
        {
          "id": "690b11fc-116c-471d-8f6c-f5a7cdcd391d",
          "name": "disableTopicRule",
          "request": {
            "url": "http://example.com/api/?Action=DisableTopicRule?ruleName=ruleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables the specified rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "66ce93aa-a6d0-4ee3-beec-8b4635316251"
            }
          ]
        },
        {
          "id": "a925693d-01f2-4559-a3b8-a61afe2daccc",
          "name": "enableTopicRule",
          "request": {
            "url": "http://example.com/api/?Action=EnableTopicRule?ruleName=ruleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables the specified rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "978e40ea-2935-4d48-8ccf-ae7d128f66a8"
            }
          ]
        },
        {
          "id": "df11f1ed-8429-457e-80e7-e894575ee2b1",
          "name": "getTopicRule",
          "request": {
            "url": "http://example.com/api/?Action=GetTopicRule?ruleName=ruleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the specified rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb663180-68db-4807-8cf9-b1220d0b6196"
            }
          ]
        }
      ]
    },
    {
      "name": "CA Certificates",
      "item": [
        {
          "id": "6275073b-36ff-43b9-9b57-c99e2daaaca4",
          "name": "deleteCACertificate",
          "request": {
            "url": "http://example.com/api/?Action=DeleteCACertificate?certificateId=certificateId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a registered CA certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4e91eaba-2f2d-483e-8363-beb1586e6f17"
            }
          ]
        },
        {
          "id": "4bb69ef9-0e33-4045-80ce-9fcc5bbdddc5",
          "name": "describeCACertificate",
          "request": {
            "url": "http://example.com/api/?Action=DescribeCACertificate?certificateId=certificateId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes a registered CA certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1c279d2b-82b4-4c1e-ae27-16f8d67e9e57"
            }
          ]
        },
        {
          "id": "c216bc04-f55c-47f4-bb14-e69d27d0ec69",
          "name": "listCACertificates",
          "request": {
            "url": "http://example.com/api/?Action=ListCACertificates?ascendingOrder=ascendingOrder&marker=marker&pageSize=pageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the CA certificates registered for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c24801d3-eaee-4778-b72a-f6aac6cc8fd5"
            }
          ]
        },
        {
          "id": "dfbf460f-48be-4c67-b954-b5d4f5ebf9d6",
          "name": "listCertificatesByCA",
          "request": {
            "url": "http://example.com/api/?Action=ListCertificatesByCA?ascendingOrder=ascendingOrder&caCertificateId=caCertificateId&marker=marker&pageSize=pageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the device certificates signed by the specified CA certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96a6acd1-0d43-46e3-a5e6-758b1fc715a6"
            }
          ]
        }
      ]
    },
    {
      "name": "Registration Codes",
      "item": [
        {
          "id": "c52bbd6e-da05-41ae-85ef-5e29176b7993",
          "name": "deleteRegistrationCode",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRegistrationCode",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a CA certificate registration code."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b63c72eb-5229-486d-8ea3-168e5c41f31c"
            }
          ]
        },
        {
          "id": "ab90afd3-4ec2-4679-9ed8-8fdbd98359ba",
          "name": "getRegistrationCode",
          "request": {
            "url": "http://example.com/api/?Action=GetRegistrationCode?registrationCode=registrationCode",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a registration code used to register a CA certificate with AWS IoT."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ca4fa5db-1920-416b-8530-bb5a043f3ffc"
            }
          ]
        }
      ]
    },
    {
      "name": "Endpoints",
      "item": [
        {
          "id": "76dd76c9-ef7f-49b3-b56f-d962923442ba",
          "name": "describeEndpoint",
          "request": {
            "url": "http://example.com/api/?Action=DescribeEndpoint?endpointAddress=endpointAddress",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a unique endpoint specific to the AWS account making the call."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9b2120e5-068e-4672-88dc-a7222e7bf562"
            }
          ]
        }
      ]
    },
    {
      "name": "Logging Options",
      "item": [
        {
          "id": "697d6db6-84b1-42ee-b9f9-f171a66d933d",
          "name": "getLoggingOptions",
          "request": {
            "url": "http://example.com/api/?Action=GetLoggingOptions?logLevel=logLevel&roleArn=roleArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the logging options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "39f93767-6bee-43d5-af28-c447e616d281"
            }
          ]
        }
      ]
    },
    {
      "name": "Policy Principals",
      "item": [
        {
          "id": "026300d6-c3be-4282-93bb-93e2eb11fdf3",
          "name": "listPolicyPrincipals",
          "request": {
            "url": "http://example.com/api/?Action=ListPolicyPrincipals?ascendingOrder=ascendingOrder&marker=marker&pageSize=pageSize&policyName=policyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the principals associated with the specified policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "806ffd13-13f3-4142-83ff-7ac8098b895e"
            }
          ]
        }
      ]
    }
  ]
}