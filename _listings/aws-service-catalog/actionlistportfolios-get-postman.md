{
  "info": {
    "name": "AWS Service Catalog API List Portfolios",
    "_postman_id": "899c9762-2e8a-45c2-a41c-ef2f9f005065",
    "description": "Lists all portfolios in the catalog.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Portfolios",
      "item": [
        {
          "id": "b5a03632-57c7-47f4-b842-db913dc3ea9e",
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
              "id": "fe9da37e-70bb-4149-8267-4dcdb72998f9"
            }
          ]
        },
        {
          "id": "c7fa8375-e320-4b03-9cca-72a3107afbf3",
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
              "id": "058157c1-a063-45d9-a55a-9e82c272a547"
            }
          ]
        },
        {
          "id": "f0e87d39-54d2-4d1b-bb5b-e69f6bffd393",
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
              "id": "3bee9fd2-8684-4e4c-b89d-c45788229285"
            }
          ]
        },
        {
          "id": "be5a9a86-104c-435f-8dc8-07681e9ee374",
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
              "id": "878614e1-07d6-437b-8d2b-1a5faee74e29"
            }
          ]
        },
        {
          "id": "20ed470b-4dc2-4889-9e9b-8a8c4f5b5aed",
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
              "id": "475f30ed-26d1-4bf3-b1df-272bc35b1380"
            }
          ]
        },
        {
          "id": "7765d5cb-05fb-43d9-ae4f-91d625066a1b",
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
              "id": "c6ad3906-be5d-4c64-b961-5a760ce81595"
            }
          ]
        },
        {
          "id": "09c3b4fe-b6a2-4b4a-9859-70b696874509",
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
              "id": "4711c589-6307-4111-b106-3123b0e67866"
            }
          ]
        },
        {
          "id": "11ca253d-ec5f-4078-b01e-0dda2bf5d67f",
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
              "id": "2a555b5e-e3a2-48ce-a7ff-5dee3e266071"
            }
          ]
        },
        {
          "id": "70dcb262-abce-4cc4-930e-35de760fe416",
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
              "id": "a1ffebc6-f591-4c13-9ab7-0163182d9361"
            }
          ]
        },
        {
          "id": "558b3058-00e6-4874-85c7-99decfb155b7",
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
              "id": "6c1a1092-957f-4b71-8c46-286a2b222d0f"
            }
          ]
        },
        {
          "id": "98e25fce-1bdd-4e85-9f43-1b0025f96cb5",
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
              "id": "04f67692-5f84-4a72-90ce-380f35a0401c"
            }
          ]
        },
        {
          "id": "12f94b13-92d6-42e0-a125-84717b8d0add",
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
              "id": "9217f72a-0417-4c8f-aa00-c7e4cd13215b"
            }
          ]
        },
        {
          "id": "98e9ca20-b1f3-4fb8-880b-a9421d1a3173",
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
              "id": "ed8d0b60-232f-471a-9f22-b2ec4ac24ce8"
            }
          ]
        },
        {
          "id": "d25009e7-fbc6-4bb5-82d1-ed007eb7d184",
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
              "id": "2ff8e7e2-75f8-45c2-b605-95b6603b535b"
            }
          ]
        }
      ]
    },
    {
      "name": "Constraints",
      "item": [
        {
          "id": "af3f9ea6-c7a3-454a-ab82-ef6d187e6211",
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
              "id": "1c74ff16-97a1-4ef3-8af9-42b7092ce3bd"
            }
          ]
        },
        {
          "id": "d1f3ddc1-0538-482e-bd5a-2fb87d7b394b",
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
              "id": "873eb963-13d4-437d-b61d-5668051a5c87"
            }
          ]
        },
        {
          "id": "145b1a64-9261-4273-83a2-d75942ff87a0",
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
              "id": "ecc32364-a328-4f8f-b3f3-e7127988e598"
            }
          ]
        }
      ]
    },
    {
      "name": "Products",
      "item": [
        {
          "id": "019a5125-84cf-4483-b42c-d894d8cf3288",
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
              "id": "99e67c85-c569-4b6d-8f44-ba6c86f48237"
            }
          ]
        },
        {
          "id": "42465cad-2f9e-4fcf-83f1-027eda4dc966",
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
              "id": "79b6a260-81da-4314-b72e-3950439ebf36"
            }
          ]
        },
        {
          "id": "1550d101-eb84-4cd1-b267-cac63832be3b",
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
              "id": "dd312487-2839-4779-a02a-8905c94f4498"
            }
          ]
        },
        {
          "id": "becb7083-4c15-4839-8eed-5e4102f4555a",
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
              "id": "35f6fac4-c97b-40b2-8dc1-7eeccdae6bad"
            }
          ]
        },
        {
          "id": "9e3e79c9-2e31-44d3-a6f4-14d2a2503f18",
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
              "id": "45030451-27eb-4710-b2b4-43174dd56d71"
            }
          ]
        }
      ]
    },
    {
      "name": "Provisioning Artifacts",
      "item": [
        {
          "id": "03f019ec-cab6-4baa-99f2-2c61d5723f2a",
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
              "id": "ffb1eb05-b894-4a08-9dfd-4dee6f715a00"
            }
          ]
        },
        {
          "id": "8997e73c-b018-456f-942b-462778c2cde7",
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
              "id": "13047c33-1b65-41b9-9e84-8de13876875b"
            }
          ]
        },
        {
          "id": "6fd349c7-081f-4186-ae3f-01dc4a3d31da",
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
              "id": "10a12fc2-284c-4248-a6d0-6074403f6bd0"
            }
          ]
        }
      ]
    },
    {
      "name": "Provisioning Parameters",
      "item": [
        {
          "id": "03b83c0d-da14-4040-813c-10163a834552",
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
              "id": "aa42354a-3276-48fd-b5cc-de6ef28d3ac7"
            }
          ]
        }
      ]
    },
    {
      "name": "Records",
      "item": [
        {
          "id": "0b89f7e2-d908-4822-8a36-f245168bd1db",
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
              "id": "51a4dfe1-b866-44a8-b12c-4b819ad75588"
            }
          ]
        }
      ]
    },
    {
      "name": "Launch Paths",
      "item": [
        {
          "id": "315828ec-abbf-4e02-8513-057b3a7f6400",
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
              "id": "8d498989-42df-4714-bfe8-e975e44544da"
            }
          ]
        }
      ]
    }
  ]
}