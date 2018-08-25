{
  "info": {
    "name": "Shopify Get a single article by its ID and the ID of the parent blog",
    "_postman_id": "6beab57f-0a9e-4b21-86d2-f445a01f7414",
    "description": "Get a single article by its id and the id of the parent blog.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commerce",
      "item": [
        {
          "id": "3e4f0e33-dce0-4813-bcc8-221884eebfbb",
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
              "id": "7ce14eed-1713-47b9-b484-785e806f3ce7"
            }
          ]
        },
        {
          "id": "cd819421-4895-404c-9c3e-1b31634c9b08",
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
              "id": "a8ed95f6-a3d8-4281-b99e-5683a1c5d4c0"
            }
          ]
        },
        {
          "id": "43c0e1a1-a7e2-4d1e-bbd6-04e4bd16edfd",
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
              "id": "d4a9dc8f-f85d-4b68-ba36-5edbad9cb876"
            }
          ]
        },
        {
          "id": "872afab8-3948-4acb-b894-e182efd019e2",
          "name": "deleteAdminBlogs62581763Articles197247246.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/blogs/62581763/articles/197247246.json",
            "method": "DELETE",
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
            "description": "Delete an article of a blog tags of articles."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "93adb7b3-5769-44ef-a56d-574b295c106e"
            }
          ]
        },
        {
          "id": "6670e7c0-a225-44ab-8bab-9c389317ea37",
          "name": "getAdminArticlesAuthors.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/articles/authors.json",
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
            "description": "Get a list of all the authors of articles."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fb2ebbed-dd84-44e1-bbc6-4fe64d2e0a55"
            }
          ]
        },
        {
          "id": "642e9a45-31ef-492d-b2c0-b758711dbbb7",
          "name": "getAdminBlogs62581763Articles196805774.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/blogs/62581763/articles/196805774.json",
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
            "description": "Get a single article by its id and the id of the parent blog."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e242839c-10c9-4866-b6f1-c142ea8f678b"
            }
          ]
        }
      ]
    }
  ]
}