{
  "info": {
    "name": "AWS Service Catalog API Update Portfolio",
    "_postman_id": "3ebf742d-3815-4f43-9960-51977f40084e",
    "description": "Updates the specified portfolio's details.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Portfolios",
      "item": [
        {
          "id": "6289c788-f482-44de-86ef-3d645f64f6ad",
          "name": "acceptPortfolioShare",
          "request": {
            "url": "http://example.com/api/?Action=AcceptPortfolioShare?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Accepts an offer to share a portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7936b09e-4a90-474a-aaac-f3e03dab54b1"
            }
          ]
        },
        {
          "id": "c9340e97-8b01-4078-9436-23df6bc30670",
          "name": "associatePrincipalWithPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=AssociatePrincipalWithPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&PrincipalARN=PrincipalARN&PrincipalType=PrincipalType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates the specified principal ARN with the specified portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0dc687e1-9b29-493f-9997-5bdaa19692d3"
            }
          ]
        },
        {
          "id": "df0e2cb3-3d56-42d9-95d1-046a8d86feaf",
          "name": "associateProductWithPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=AssociateProductWithPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&ProductId=ProductId&SourcePortfolioId=SourcePortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates a product with a portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d20d440-1ee2-4f7e-bf41-a6e998a113ba"
            }
          ]
        },
        {
          "id": "ea06db85-0720-4e55-9258-d756070dd85c",
          "name": "createPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=CreatePortfolio?AcceptLanguage=AcceptLanguage&Description=Description&DisplayName=DisplayName&IdempotencyToken=IdempotencyToken&ProviderName=ProviderName&Tags=Tags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d051d7a-b7a0-4314-ab13-b13137d66cb9"
            }
          ]
        },
        {
          "id": "af754e6b-4c5e-4373-b0a1-32887e3fb70d",
          "name": "createPortfolioShare",
          "request": {
            "url": "http://example.com/api/?Action=CreatePortfolioShare?AcceptLanguage=AcceptLanguage&AccountId=AccountId&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new portfolio share."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2797d8fd-a082-4136-90bd-d6c1dfd3c48f"
            }
          ]
        },
        {
          "id": "226cd7d7-1ecf-43a9-9fe9-7bf1023e1cc5",
          "name": "deletePortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DeletePortfolio?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cac94190-a85b-476e-926d-cd38aa767161"
            }
          ]
        },
        {
          "id": "8080b349-e177-4013-9705-ac38760cba89",
          "name": "deletePortfolioShare",
          "request": {
            "url": "http://example.com/api/?Action=DeletePortfolioShare?AcceptLanguage=AcceptLanguage&AccountId=AccountId&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified portfolio share."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d4d1e1a0-e797-4347-ac16-dca3993cc7e2"
            }
          ]
        },
        {
          "id": "1a8e5900-4e43-4082-a178-6bea6df26796",
          "name": "describePortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DescribePortfolio?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed information and any tags associated with the specified\n         portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "80222f61-9a52-427f-8db7-80d5aabbc5b3"
            }
          ]
        },
        {
          "id": "7c903f1e-7eb6-4a1c-99b2-35db0b5fe67e",
          "name": "disassociatePrincipalFromPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DisassociatePrincipalFromPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&PrincipalARN=PrincipalARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates a previously associated principal ARN from a specified\n         portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d7138ca2-f152-4fa3-9105-b55d13eab08e"
            }
          ]
        },
        {
          "id": "d01006be-7ea9-4c50-ae40-806dfc180c23",
          "name": "disassociateProductFromPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateProductFromPortfolio?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates the specified product from the specified portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c7017971-d6e1-4a0f-93b2-1a1a68d65e2c"
            }
          ]
        },
        {
          "id": "2d0088d1-ca2a-4897-b3f2-f60f385952a2",
          "name": "listAcceptedPortfolioShares",
          "request": {
            "url": "http://example.com/api/?Action=ListAcceptedPortfolioShares?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists details of all portfolios for which sharing was accepted by this\n         account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "90f41287-fc52-4baa-9012-42cb944b97cb"
            }
          ]
        },
        {
          "id": "2443f2f2-2633-45f5-90e3-da95ae13c213",
          "name": "listConstraintsForPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=ListConstraintsForPortfolio?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken&PortfolioId=PortfolioId&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed constraint information for the specified portfolio and\n         product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "47a78ae6-7f0e-4809-9938-7197958e6058"
            }
          ]
        },
        {
          "id": "594cc84c-4676-43c0-b81a-a45ac9c655fc",
          "name": "listPortfolioAccess",
          "request": {
            "url": "http://example.com/api/?Action=ListPortfolioAccess?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the account IDs that have been authorized sharing of the specified\n         portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ffbdb92f-72b1-4631-9ada-01a5bf921676"
            }
          ]
        },
        {
          "id": "606ba8a8-2753-4e67-93a5-b5266d5c7edf",
          "name": "listPortfolios",
          "request": {
            "url": "http://example.com/api/?Action=ListPortfolios?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all portfolios in the catalog."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "90950fde-38c5-4c9a-a29d-cdab6a310566"
            }
          ]
        },
        {
          "id": "1fa5f9a4-4117-4dfc-92fa-cde3773e9cde",
          "name": "listPortfoliosForProduct",
          "request": {
            "url": "http://example.com/api/?Action=ListPortfoliosForProduct?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all portfolios that the specified product is associated with."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "56a526de-434a-48ea-a43f-795b110263f6"
            }
          ]
        },
        {
          "id": "a5c32734-c9a7-48a7-bc50-a753b2b84225",
          "name": "listPrincipalsForPortfolio",
          "request": {
            "url": "http://example.com/api/?Action=ListPrincipalsForPortfolio?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all principal ARNs associated with the specified portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c18f0d6-f812-4063-8e91-1f79c67528d1"
            }
          ]
        },
        {
          "id": "ec5b8f22-509f-4dcf-8d6c-cf5f54f5ce7e",
          "name": "rejectPortfolioShare",
          "request": {
            "url": "http://example.com/api/?Action=RejectPortfolioShare?AcceptLanguage=AcceptLanguage&PortfolioId=PortfolioId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Rejects an offer to share a portfolio."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2754ec8c-3b2e-4017-bd72-175c614ec467"
            }
          ]
        },
        {
          "id": "06aac2a1-6d9c-451b-b496-e33b34260830",
          "name": "updatePortfolio",
          "request": {
            "url": "http://example.com/api/?Action=UpdatePortfolio?AcceptLanguage=AcceptLanguage&AddTags=AddTags&Description=Description&DisplayName=DisplayName&Id=Id&ProviderName=ProviderName&RemoveTags=RemoveTags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the specified portfolio's details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1cfaead7-3148-4fd7-aa73-87b664e4cebd"
            }
          ]
        }
      ]
    },
    {
      "name": "Constraints",
      "item": [
        {
          "id": "4d014818-c5fc-4f9d-a1e3-b40e1201657b",
          "name": "createConstraint",
          "request": {
            "url": "http://example.com/api/?Action=CreateConstraint?AcceptLanguage=AcceptLanguage&Description=Description&IdempotencyToken=IdempotencyToken&Parameters=Parameters&PortfolioId=PortfolioId&ProductId=ProductId&Type=Type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new constraint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "49ea150b-1979-40ef-a1fe-8e49329816d9"
            }
          ]
        },
        {
          "id": "e4dcf188-500e-4a66-aafb-c0e998aaeffc",
          "name": "deleteConstraint",
          "request": {
            "url": "http://example.com/api/?Action=DeleteConstraint?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified constraint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "071a5526-723f-4299-b986-60a1a6530815"
            }
          ]
        },
        {
          "id": "a3fef31b-11cb-4fad-bd8f-04816fe34f7d",
          "name": "describeConstraint",
          "request": {
            "url": "http://example.com/api/?Action=DescribeConstraint?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed information for a specified constraint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de5a157c-7aa0-47ad-aef6-24ddb182fe21"
            }
          ]
        },
        {
          "id": "33ffe983-3772-459b-ad95-855dc3e7bac0",
          "name": "updateConstraint",
          "request": {
            "url": "http://example.com/api/?Action=UpdateConstraint?AcceptLanguage=AcceptLanguage&Description=Description&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates an existing constraint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03d1a706-e749-47b0-ad3f-53e5b14105ec"
            }
          ]
        }
      ]
    },
    {
      "name": "Products",
      "item": [
        {
          "id": "92d54799-f8db-4168-b582-e440d91e8680",
          "name": "createProduct",
          "request": {
            "url": "http://example.com/api/?Action=CreateProduct?AcceptLanguage=AcceptLanguage&Description=Description&Distributor=Distributor&IdempotencyToken=IdempotencyToken&Name=Name&Owner=Owner&ProductType=ProductType&ProvisioningArtifactParameters=ProvisioningArtifactParameters&SupportDescription=SupportDescription&SupportEmail=SupportEmail&SupportUrl=SupportUrl&Tags=Tags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f79afa9f-7f2a-4831-a8ae-2c814fc404f7"
            }
          ]
        },
        {
          "id": "fe7170d1-7af7-4894-bfbb-1935e70ac6df",
          "name": "deleteProduct",
          "request": {
            "url": "http://example.com/api/?Action=DeleteProduct?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7910e803-b880-4d97-b8d0-73ee3b409249"
            }
          ]
        },
        {
          "id": "e8160084-853d-41b3-8ff9-16440d9852f2",
          "name": "describeProduct",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProduct?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d92b26d-bb63-410e-a923-927c0cd76d1c"
            }
          ]
        },
        {
          "id": "9a334750-b4f5-4d42-9e51-5c4ba0d10fc0",
          "name": "describeProductAsAdmin",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProductAsAdmin?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a specified product, run with administrator\n         access."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ac06dfba-56eb-4df5-bfd8-3300f58b47b3"
            }
          ]
        },
        {
          "id": "36256ada-40ce-46fc-8402-ead9af0d6f33",
          "name": "describeProductView",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProductView?AcceptLanguage=AcceptLanguage&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f63bdd6f-62a6-4130-a453-0ceb7587e392"
            }
          ]
        },
        {
          "id": "99797119-1671-42f5-be43-cb212468fef7",
          "name": "provisionProduct",
          "request": {
            "url": "http://example.com/api/?Action=ProvisionProduct?AcceptLanguage=AcceptLanguage&NotificationArns=NotificationArns&PathId=PathId&ProductId=ProductId&ProvisionedProductName=ProvisionedProductName&ProvisioningArtifactId=ProvisioningArtifactId&ProvisioningParameters=ProvisioningParameters&ProvisionToken=ProvisionToken&Tags=Tags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a Provision of a specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "80e93a90-5339-4fae-8ad5-98fc9c991ae9"
            }
          ]
        },
        {
          "id": "96c973ae-3242-4fb2-a5d6-782715b1015b",
          "name": "searchProducts",
          "request": {
            "url": "http://example.com/api/?Action=SearchProducts?AcceptLanguage=AcceptLanguage&Filters=Filters&PageSize=PageSize&PageToken=PageToken&SortBy=SortBy&SortOrder=SortOrder",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a paginated list all of the Products objects to which the caller\n         has access."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c2e715a6-ba00-4409-be0a-489132f50619"
            }
          ]
        },
        {
          "id": "dc0d3f25-59bf-444c-b30f-b72021cd41ca",
          "name": "searchProductsAsAdmin",
          "request": {
            "url": "http://example.com/api/?Action=SearchProductsAsAdmin?AcceptLanguage=AcceptLanguage&Filters=Filters&PageSize=PageSize&PageToken=PageToken&PortfolioId=PortfolioId&ProductSource=ProductSource&SortBy=SortBy&SortOrder=SortOrder",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves summary and status information about all products created within the\n         caller's account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea2b17f3-a047-47a2-9f0a-9de3f33baac4"
            }
          ]
        }
      ]
    },
    {
      "name": "Provisioning Artifacts",
      "item": [
        {
          "id": "3d0070e4-f1e8-48ae-b897-e1efcf5cb885",
          "name": "createProvisioningArtifact",
          "request": {
            "url": "http://example.com/api/?Action=CreateProvisioningArtifact?AcceptLanguage=AcceptLanguage&IdempotencyToken=IdempotencyToken&Parameters=Parameters&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Create a new provisioning artifact for the specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89f7df03-4a41-4244-8571-3f0cce17159a"
            }
          ]
        },
        {
          "id": "6973ded9-ba5a-4020-8542-b1d2c890554b",
          "name": "deleteProvisioningArtifact",
          "request": {
            "url": "http://example.com/api/?Action=DeleteProvisioningArtifact?AcceptLanguage=AcceptLanguage&ProductId=ProductId&ProvisioningArtifactId=ProvisioningArtifactId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified provisioning artifact."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "05bb3704-5fd5-46ff-9685-7bfb92bb41f3"
            }
          ]
        },
        {
          "id": "dc5a3ea8-fa90-4dc1-bad9-1d9f8a81f315",
          "name": "describeProvisioningArtifact",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProvisioningArtifact?AcceptLanguage=AcceptLanguage&ProductId=ProductId&ProvisioningArtifactId=ProvisioningArtifactId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves detailed information about the specified provisioning artifact."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "82273a13-de47-49a3-837c-3e2cfb5c1e30"
            }
          ]
        },
        {
          "id": "067162b8-8530-45fc-a72d-82730b0bc64d",
          "name": "listProvisioningArtifacts",
          "request": {
            "url": "http://example.com/api/?Action=ListProvisioningArtifacts?AcceptLanguage=AcceptLanguage&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all provisioning artifacts associated with the specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03d203e0-4aad-4cb7-b671-930c2c64a499"
            }
          ]
        }
      ]
    },
    {
      "name": "Provisioning Parameters",
      "item": [
        {
          "id": "6716fd46-a305-4307-985a-08cd603caf88",
          "name": "describeProvisioningParameters",
          "request": {
            "url": "http://example.com/api/?Action=DescribeProvisioningParameters?AcceptLanguage=AcceptLanguage&PathId=PathId&ProductId=ProductId&ProvisioningArtifactId=ProvisioningArtifactId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides information about parameters required to provision a specified product in a\n         specified manner."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8950a07d-9b0b-479c-af5a-68647dc78566"
            }
          ]
        }
      ]
    },
    {
      "name": "Records",
      "item": [
        {
          "id": "448486e7-1d18-4c4c-85cb-dad4cd4720d2",
          "name": "describeRecord",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRecord?AcceptLanguage=AcceptLanguage&Id=Id&PageSize=PageSize&PageToken=PageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a paginated list of the full details of a specific request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "63067f68-9d18-417f-8bfd-fb597ae1d2e0"
            }
          ]
        }
      ]
    },
    {
      "name": "Launch Paths",
      "item": [
        {
          "id": "f63f4b38-b45f-416c-a6b2-1590ef84eafa",
          "name": "listLaunchPaths",
          "request": {
            "url": "http://example.com/api/?Action=ListLaunchPaths?AcceptLanguage=AcceptLanguage&PageSize=PageSize&PageToken=PageToken&ProductId=ProductId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a paginated list of all paths to a specified product."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "12aa9f78-733a-4c5c-9966-db67024884a4"
            }
          ]
        }
      ]
    },
    {
      "name": "Record History",
      "item": [
        {
          "id": "d7350310-c002-4110-83c4-6b0b8fe0925d",
          "name": "listRecordHistory",
          "request": {
            "url": "http://example.com/api/?Action=ListRecordHistory?AcceptLanguage=AcceptLanguage&AccessLevelFilter=AccessLevelFilter&PageSize=PageSize&PageToken=PageToken&SearchFilter=SearchFilter",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a paginated list of all performed requests, in the form of RecordDetails\n         objects that are filtered as specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "87ad1c61-a899-4d14-927a-84c1a9437baf"
            }
          ]
        }
      ]
    },
    {
      "name": "Provisioned Products",
      "item": [
        {
          "id": "7bc471d1-1490-48fc-bcee-c5cd5547da5d",
          "name": "scanProvisionedProducts",
          "request": {
            "url": "http://example.com/api/?Action=ScanProvisionedProducts?AcceptLanguage=AcceptLanguage&AccessLevelFilter=AccessLevelFilter&PageSize=PageSize&PageToken=PageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a paginated list of all the ProvisionedProduct objects that are currently\n         available (not terminated)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a47175fa-7e95-4e26-9557-fc719a4e9bf2"
            }
          ]
        },
        {
          "id": "40d4c1db-707a-4251-83c3-f1054b7cc97f",
          "name": "terminateProvisionedProduct",
          "request": {
            "url": "http://example.com/api/?Action=TerminateProvisionedProduct?AcceptLanguage=AcceptLanguage&IgnoreErrors=IgnoreErrors&ProvisionedProductId=ProvisionedProductId&ProvisionedProductName=ProvisionedProductName&TerminateToken=TerminateToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests termination of an existing ProvisionedProduct object."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd2a55bb-3fea-443e-9c1d-5e8dc0c44d1a"
            }
          ]
        }
      ]
    }
  ]
}