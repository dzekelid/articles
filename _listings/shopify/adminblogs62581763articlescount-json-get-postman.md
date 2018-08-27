{
  "info": {
    "name": "Shopify Get a count of all articles from a certain blog",
    "_postman_id": "92e9d22f-6867-4341-a53a-86c95806f7ef",
    "description": "Get a count of all articles from a certain blog.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commerce",
      "item": [
        {
          "id": "1b22c80e-286e-4ed5-9e4d-de6c7948d784",
          "name": "getAdminBlogs62581763Articles.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/blogs/62581763/articles.json",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of all articles from a certain blog."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6910dbe4-8286-4e4b-a74e-024b3650bef4"
            }
          ]
        },
        {
          "id": "7d1ea034-e777-43ae-9f7f-2cda4b4ccb50",
          "name": "getAdminBlogs62581763ArticlesCount.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/blogs/62581763/articles/count.json",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a count of all articles from a certain blog."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f14f8ab7-2758-4f72-b8b7-a93bc016a873"
            }
          ]
        }
      ]
    }
  ]
}