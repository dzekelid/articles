{
  "info": {
    "name": "Shopify Get a list of all the authors of articles",
    "_postman_id": "c7649aa1-3fc1-47d0-b556-b8d704fe80b1",
    "description": "Get a list of all the authors of articles.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commerce",
      "item": [
        {
          "id": "81d6cd76-4de2-402a-89f7-24c01b1b9ce1",
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
              "id": "425e49ff-8dde-48c4-bb46-b892a5ce9c5f"
            }
          ]
        },
        {
          "id": "44cce126-4a16-4c05-aef1-b3fb968734a8",
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
              "id": "a6e518f8-b095-42ab-95c2-bedf0879c721"
            }
          ]
        },
        {
          "id": "6d9826dc-0fa7-43cd-bf8f-a0b0505f7186",
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
              "id": "2d2e4aba-5639-4291-b682-6b360b580db1"
            }
          ]
        },
        {
          "id": "c4ac5929-efaf-4d5b-9737-02765264bdfc",
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
              "id": "313880e7-883e-46c2-bee8-f45665013d88"
            }
          ]
        },
        {
          "id": "e25a03a8-35d0-4966-a521-239f36706194",
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
              "id": "5062dc5a-7ba1-4296-bc71-237aea56984e"
            }
          ]
        }
      ]
    }
  ]
}