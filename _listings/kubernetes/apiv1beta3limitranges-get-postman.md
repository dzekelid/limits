{
  "info": {
    "name": "Kubernetes Get Limitranges",
    "_postman_id": "291110de-dfa3-4b62-8098-5367a0fcabb2",
    "description": "List objects of kind limitrange.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Endpoints",
      "item": [
        {
          "id": "62857de5-3c5f-4770-b459-1984e34fec41",
          "name": "listEndpoints",
          "request": {
            "url": "http:///api/v1beta3/127.0.0.1:6443/api/v1beta3/endpoints",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List objects of kind endpoints."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b900ae5c-a133-4470-a611-21add5401331"
            }
          ]
        }
      ]
    },
    {
      "name": "Events",
      "item": [
        {
          "id": "6979f5d3-8d29-41e2-ae2b-526cf7bb9489",
          "name": "listEvent",
          "request": {
            "url": "http:///api/v1beta3/127.0.0.1:6443/api/v1beta3/events",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List objects of kind event."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e01b1789-22e7-4834-be2c-984d148e37e2"
            }
          ]
        }
      ]
    },
    {
      "name": "Limitranges",
      "item": [
        {
          "id": "123154bc-304a-4a8c-8f1c-58d2c2b7475d",
          "name": "listLimitRange",
          "request": {
            "url": "http:///api/v1beta3/127.0.0.1:6443/api/v1beta3/limitranges",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List objects of kind limitrange."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd5014ac-95d7-4d64-95a2-3a2e90ea6cfe"
            }
          ]
        }
      ]
    }
  ]
}