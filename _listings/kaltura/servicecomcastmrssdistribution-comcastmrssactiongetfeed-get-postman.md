{
  "info": {
    "name": "Kaltura VPaaS Get Service Comcastmrssdistribution Comcastmrss Action Getfeed",
    "_postman_id": "1adeabe5-965a-43ea-86ed-efa9bd1f9a99",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "4b5f1925-dbf8-4926-a1ca-0c8819220c0e",
          "name": "attUverse.getFeed",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attuversedistribution_attuverse/action/getFeed?distributionProfileId=%7B%7D&hash=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Service Attuversedistribution Attuverse Action Getfeed"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b4a661d-6291-421f-bc86-640c96c623c7"
            }
          ]
        },
        {
          "id": "78d617ab-ead1-4273-b2d8-9b55a920cfb0",
          "name": "avn.getFeed",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/avndistribution_avn/action/getFeed?distributionProfileId=%7B%7D&hash=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Service Avndistribution Avn Action Getfeed"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c4b64064-414d-4f92-9d06-1493aa2dfce7"
            }
          ]
        },
        {
          "id": "70bb7adf-1f0c-4a0b-b07d-3df0079f3a05",
          "name": "comcastMrss.getFeed",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/comcastmrssdistribution_comcastmrss/action/getFeed?distributionProfileId=%7B%7D&hash=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Service Comcastmrssdistribution Comcastmrss Action Getfeed"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ea2170b-7fe0-4a09-b435-ad89017eebf7"
            }
          ]
        }
      ]
    }
  ]
}