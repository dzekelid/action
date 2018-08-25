{
  "info": {
    "name": "AWS Service Catalog API Accept Portfolio Share",
    "_postman_id": "75afbfc8-a682-49a9-b2b2-4b546a23379b",
    "description": "Accepts an offer to share a portfolio.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Portfolios",
      "item": [
        {
          "id": "83f4997f-49e0-4af1-ad54-9f62881e3110",
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
              "id": "725ea1b7-717e-4d21-ad44-c223ff782d92"
            }
          ]
        }
      ]
    }
  ]
}