{
  "info": {
    "name": "Shopify Get a list of all the tags of articles",
    "_postman_id": "d4094dbd-7af3-4366-b559-c6510bcb4ab7",
    "description": "Get a list of all the tags of articles.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commerce",
      "item": [
        {
          "id": "abf1e87d-732c-4e0b-b79a-a265a5fab419",
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
              "id": "68ea05ae-f594-469e-a412-21dae5653053"
            }
          ]
        },
        {
          "id": "8db67f2d-be47-47a7-9c2f-ec21dea4bc99",
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
              "id": "7bf5a36d-fca3-424c-812e-40d63e6a6757"
            }
          ]
        },
        {
          "id": "f94e2759-d78e-45bc-9884-c902cec10f00",
          "name": "getAdminArticlesTags.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/articles/tags.json",
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
            "description": "Get a list of all the tags of articles."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69532a25-f9b6-4ee3-901e-7f131f5559d0"
            }
          ]
        }
      ]
    }
  ]
}