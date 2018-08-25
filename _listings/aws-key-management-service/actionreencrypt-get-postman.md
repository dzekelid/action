{
  "info": {
    "name": "AWS Key Management Service API Re Encrypt",
    "_postman_id": "8a0fe8b8-08cd-4936-b19e-3e0ace267141",
    "description": "Encrypts data on the server side with a new customer master key (CMK) without exposing\n      the plaintext of the data on the client side.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Keys",
      "item": [
        {
          "id": "f359a3cb-21ba-47ab-8749-856bd7f8c2da",
          "name": "cancelKeyDeletion",
          "request": {
            "url": "http://example.com/api/?Action=CancelKeyDeletion?KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels the deletion of a customer master key (CMK)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9a7f1a3-5453-4fd1-8905-bdc288b45380"
            }
          ]
        },
        {
          "id": "beabf70f-6773-4fe6-a9ee-082b86c946af",
          "name": "createKey",
          "request": {
            "url": "http://example.com/api/?Action=CreateKey?BypassPolicyLockoutSafetyCheck=BypassPolicyLockoutSafetyCheck&Description=Description&KeyUsage=KeyUsage&Origin=Origin&Policy=Policy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a customer master key (CMK)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ab48ca4-02d1-479b-9036-721f2bf2a513"
            }
          ]
        },
        {
          "id": "d6dccbe4-cea0-4026-bd22-d5e3ff1b76ae",
          "name": "deleteImportedKeyMaterial",
          "request": {
            "url": "http://example.com/api/?Action=DeleteImportedKeyMaterial?KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes key material that you previously imported and makes the specified customer\n      master key (CMK) unusable."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df588db5-17c4-4f08-9223-98585950eb07"
            }
          ]
        },
        {
          "id": "74714b7f-c93a-4829-9587-cd527e93d604",
          "name": "describeKey",
          "request": {
            "url": "http://example.com/api/?Action=DescribeKey?GrantTokens=GrantTokens&KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides detailed information about the specified customer master key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "181fa68d-c2ca-424f-b39b-b09947cdeffa"
            }
          ]
        },
        {
          "id": "20bbbef0-1d52-4def-890c-53aafdd195b5",
          "name": "disableKey",
          "request": {
            "url": "http://example.com/api/?Action=DisableKey?KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the state of a customer master key (CMK) to disabled, thereby preventing its use\n      for cryptographic operations."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "566d705d-2c48-4f23-85e4-d5d321109f03"
            }
          ]
        },
        {
          "id": "27e1a037-7ee0-41d0-a435-c541a69202b1",
          "name": "disableKeyRotation",
          "request": {
            "url": "http://example.com/api/?Action=DisableKeyRotation?KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables rotation of the specified key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d5ee021f-38ad-422e-883c-ce02ddc920af"
            }
          ]
        },
        {
          "id": "b00166d2-91a6-4abb-bdd3-8412006296ed",
          "name": "enableKey",
          "request": {
            "url": "http://example.com/api/?Action=EnableKey?KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Marks a key as enabled, thereby permitting its use."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "155d1b0d-5852-4b7b-aa20-da72b085bb7e"
            }
          ]
        },
        {
          "id": "50a8aec8-adea-4c0e-bea4-7e675b897264",
          "name": "enableKeyRotation",
          "request": {
            "url": "http://example.com/api/?Action=EnableKeyRotation?KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables rotation of the specified customer master key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3d43a6cb-51af-43db-93a1-c510682159da"
            }
          ]
        },
        {
          "id": "72ad562d-d6d2-4588-ae07-2f3cc23288ea",
          "name": "generateDataKey",
          "request": {
            "url": "http://example.com/api/?Action=GenerateDataKey?EncryptionContext=EncryptionContext&GrantTokens=GrantTokens&KeyId=KeyId&KeySpec=KeySpec&NumberOfBytes=NumberOfBytes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a data encryption key that you can use in your application to encrypt\n      data locally."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e9cf93dd-4817-402f-a6d3-79313d9d2cf2"
            }
          ]
        },
        {
          "id": "e073e940-23bb-4348-9ee5-511ff2ae57e6",
          "name": "generateDataKeyWithoutPlaintext",
          "request": {
            "url": "http://example.com/api/?Action=GenerateDataKeyWithoutPlaintext?EncryptionContext=EncryptionContext&GrantTokens=GrantTokens&KeyId=KeyId&KeySpec=KeySpec&NumberOfBytes=NumberOfBytes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a data encryption key encrypted under a customer master key (CMK)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0bca6529-9844-4f6e-803f-9b12a1ced4b3"
            }
          ]
        },
        {
          "id": "809528cd-b621-4cb8-93de-aa9a76907742",
          "name": "getKeyRotationStatus",
          "request": {
            "url": "http://example.com/api/?Action=GetKeyRotationStatus?KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a Boolean value that indicates whether key rotation is enabled for the\n      specified key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0ff4c08-3af5-48bb-97ea-9bb9391a728d"
            }
          ]
        },
        {
          "id": "cc94be59-6f04-4d94-8d3d-6d76fc71acf0",
          "name": "importKeyMaterial",
          "request": {
            "url": "http://example.com/api/?Action=ImportKeyMaterial?EncryptedKeyMaterial=EncryptedKeyMaterial&ExpirationModel=ExpirationModel&ImportToken=ImportToken&KeyId=KeyId&ValidTo=ValidTo",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Imports key material into an AWS KMS customer master key (CMK) from your existing key\n      management infrastructure."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2000f4bd-1fab-4277-b508-23309f11b9d1"
            }
          ]
        },
        {
          "id": "e750e2d9-8a0c-44a7-8211-cc3266824e19",
          "name": "listKeys",
          "request": {
            "url": "http://example.com/api/?Action=ListKeys?Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the customer master keys."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f66dcb1f-b2d2-4f86-872c-a1517cd5b91c"
            }
          ]
        },
        {
          "id": "876f991c-5368-41ce-af1a-8b108c3d9e58",
          "name": "putKeyPolicy",
          "request": {
            "url": "http://example.com/api/?Action=PutKeyPolicy?BypassPolicyLockoutSafetyCheck=BypassPolicyLockoutSafetyCheck&KeyId=KeyId&Policy=Policy&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches a key policy to the specified customer master key (CMK)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9834d408-c111-4c88-b78b-0e0015fce116"
            }
          ]
        }
      ]
    },
    {
      "name": "Aliases",
      "item": [
        {
          "id": "c8999160-ee50-4a75-95b6-d55ac256fc89",
          "name": "createAlias",
          "request": {
            "url": "http://example.com/api/?Action=CreateAlias?AliasName=AliasName&TargetKeyId=TargetKeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a display name for a customer master key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "01d451cd-ca5d-47c1-ba7e-d8480ae60e35"
            }
          ]
        },
        {
          "id": "e5db2c0d-b4a7-423f-ae15-bdc31bf78d38",
          "name": "deleteAlias",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAlias?AliasName=AliasName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified alias."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e93e4f4-993a-4de9-8214-ef86725d45a6"
            }
          ]
        },
        {
          "id": "4370f424-e534-4c13-aee8-40824478e2fb",
          "name": "listAliases",
          "request": {
            "url": "http://example.com/api/?Action=ListAliases?Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all of the key aliases in the account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a2f0d427-accf-4bbf-bc09-88eb542388f4"
            }
          ]
        }
      ]
    },
    {
      "name": "Grants",
      "item": [
        {
          "id": "3d5db2e0-38c2-414e-8dca-dcb9d0c2b422",
          "name": "createGrant",
          "request": {
            "url": "http://example.com/api/?Action=CreateGrant?Constraints=Constraints&GranteePrincipal=GranteePrincipal&GrantTokens=GrantTokens&KeyId=KeyId&Name=Name&Operations=Operations&RetiringPrincipal=RetiringPrincipal",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds a grant to a key to specify who can use the key and under what conditions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34c7d2f5-e105-4b2c-9bc4-577b04dd12e5"
            }
          ]
        },
        {
          "id": "54265657-1848-4616-8e5a-eb0d718d395a",
          "name": "listGrants",
          "request": {
            "url": "http://example.com/api/?Action=ListGrants?KeyId=KeyId&Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the grants for a specified key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9509409-94c3-4e5e-8d89-6621d8475eaa"
            }
          ]
        },
        {
          "id": "525e3c24-4d28-4567-8cd6-b1c0039f4b87",
          "name": "listRetirableGrants",
          "request": {
            "url": "http://example.com/api/?Action=ListRetirableGrants?Limit=Limit&Marker=Marker&RetiringPrincipal=RetiringPrincipal",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of all grants for which the grant's RetiringPrincipal\n      matches the one specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4619d504-9682-42b0-a7e7-f870399db62f"
            }
          ]
        }
      ]
    },
    {
      "name": "Decrypt",
      "item": [
        {
          "id": "5648878a-4fca-46d9-8117-e663326bfd14",
          "name": "decrypt",
          "request": {
            "url": "http://example.com/api/?Action=Decrypt?CiphertextBlob=CiphertextBlob&EncryptionContext=EncryptionContext&GrantTokens=GrantTokens",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Decrypts ciphertext."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da71192b-69ab-421d-a018-269dbf4a5acf"
            }
          ]
        }
      ]
    },
    {
      "name": "Encrypt",
      "item": [
        {
          "id": "1124cde6-67ce-4b78-8dc6-d6ec7407b1d7",
          "name": "encrypt",
          "request": {
            "url": "http://example.com/api/?Action=Encrypt?EncryptionContext=EncryptionContext&GrantTokens=GrantTokens&KeyId=KeyId&Plaintext=Plaintext",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Encrypts plaintext into ciphertext by using a customer master key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27bfec73-b7de-429b-bde8-ef90b792392b"
            }
          ]
        },
        {
          "id": "e9f39f68-c3fc-4c35-a9bc-6b4d1a4bf415",
          "name": "reEncrypt",
          "request": {
            "url": "http://example.com/api/?Action=ReEncrypt?CiphertextBlob=CiphertextBlob&DestinationEncryptionContext=DestinationEncryptionContext&DestinationKeyId=DestinationKeyId&GrantTokens=GrantTokens&SourceEncryptionContext=SourceEncryptionContext",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Encrypts data on the server side with a new customer master key (CMK) without exposing\n      the plaintext of the data on the client side."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d5799a0c-cb5e-488a-8929-5756e7638878"
            }
          ]
        }
      ]
    },
    {
      "name": "Randoms",
      "item": [
        {
          "id": "989bd784-d24d-493f-881c-144b46ffcd02",
          "name": "generateRandom",
          "request": {
            "url": "http://example.com/api/?Action=GenerateRandom?NumberOfBytes=NumberOfBytes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates an unpredictable byte string."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f2fe522-124e-430b-ad17-bb5e63488514"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Policies",
      "item": [
        {
          "id": "39b87703-92c9-4420-bcbd-8e135937fd58",
          "name": "getKeyPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetKeyPolicy?KeyId=KeyId&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a policy attached to the specified key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fbeb59e0-3439-40ca-b252-7c68039c28aa"
            }
          ]
        }
      ]
    },
    {
      "name": "Parameters",
      "item": [
        {
          "id": "646e234a-b8ac-4e8d-8c51-961563ae032b",
          "name": "getParametersForImport",
          "request": {
            "url": "http://example.com/api/?Action=GetParametersForImport?KeyId=KeyId&WrappingAlgorithm=WrappingAlgorithm&WrappingKeySpec=WrappingKeySpec",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the items you need in order to import key material into AWS KMS from your\n      existing key management infrastructure."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c5bd153a-87e8-46f9-a5ab-64ced5a7e1a2"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "cca85628-e108-4c93-82c9-32be890bb981",
          "name": "listKeyPolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListKeyPolicies?KeyId=KeyId&Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a list of policies attached to a key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7b7c7578-0f25-436d-852e-dcbb639c6c96"
            }
          ]
        }
      ]
    }
  ]
}