{
  "info": {
    "name": "AWS Key Management Service API Encrypt",
    "_postman_id": "d1e8ca28-03b2-4e60-913a-7cd03824e7d1",
    "description": "Encrypts plaintext into ciphertext by using a customer master key.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Keys",
      "item": [
        {
          "id": "52436cc8-8ac2-48a5-83a2-4deb172a0df6",
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
              "id": "5b7e3de7-1ed6-420d-a9b9-19048e8f399c"
            }
          ]
        },
        {
          "id": "f133605a-5bd9-4575-b4cf-b343d02d668c",
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
              "id": "7b97207e-f2b6-4d4c-97fa-8671548d7664"
            }
          ]
        },
        {
          "id": "c0210baa-817f-4cbb-8337-0b028a028f2e",
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
              "id": "47172f95-c5f5-4807-befa-4d160274d84b"
            }
          ]
        },
        {
          "id": "e6615e29-81a4-44e5-abb6-70db524ae4fa",
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
              "id": "c7f036b1-b4c6-46c0-b701-3417ef9cfa14"
            }
          ]
        },
        {
          "id": "13a15d03-c4cc-4c71-9dd9-a2a03bef5032",
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
              "id": "b8391053-6b53-4e35-81a6-a3f08df08aa3"
            }
          ]
        },
        {
          "id": "7b11230e-5900-4837-b38d-4bef9e388c72",
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
              "id": "303424bb-8e46-41d9-b36a-3165c3b87492"
            }
          ]
        },
        {
          "id": "458e7138-9783-416a-86e7-67ff680bdb54",
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
              "id": "af22ef20-35f9-4123-84c3-622a4ab32989"
            }
          ]
        },
        {
          "id": "c539a60a-b323-4296-9722-61b713f48a18",
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
              "id": "8fd0e460-73b2-4b46-bb7c-5acf4adf79d4"
            }
          ]
        }
      ]
    },
    {
      "name": "Aliases",
      "item": [
        {
          "id": "4494659e-6c93-4b73-a658-b966132ef5e8",
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
              "id": "bf6d3bd4-f1c4-4ab1-a041-4477315f017a"
            }
          ]
        },
        {
          "id": "77ae2e6d-288d-4d8e-96a4-0e12277e062e",
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
              "id": "9b65029e-7dce-4000-8bbb-a9b3cda81452"
            }
          ]
        }
      ]
    },
    {
      "name": "Grants",
      "item": [
        {
          "id": "a2f45470-1c62-4aa2-8e2b-c94a907e0d04",
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
              "id": "b6dbb931-e13f-4427-87b8-6bdc61de9ee8"
            }
          ]
        }
      ]
    },
    {
      "name": "Decrypt",
      "item": [
        {
          "id": "f21889bb-b289-43da-b237-7803d78b6573",
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
              "id": "195370cf-ff3a-4acb-813c-eb2104010005"
            }
          ]
        }
      ]
    },
    {
      "name": "Encrypt",
      "item": [
        {
          "id": "518c0804-339d-4388-9988-67038e0207ee",
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
              "id": "7e922823-5407-42d4-8290-3f13752c0cd2"
            }
          ]
        }
      ]
    }
  ]
}