{
  "info": {
    "name": "Shopify Get a list of all articles from a certain blog",
    "_postman_id": "5f1187bd-9c9d-477b-8428-1df034af9e93",
    "description": "Get a list of all articles from a certain blog.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commerce",
      "item": [
        {
          "id": "9ba20bc6-40ea-4bbc-92ff-e67119c56fe2",
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
              "id": "aa29a7a6-6fac-456d-97c4-9ba6ad94983f"
            }
          ]
        }
      ]
    }
  ]
}