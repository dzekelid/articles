{
  "info": {
    "name": "Vestorly Get Articles",
    "_postman_id": "ad03e5a6-1141-498d-9012-c51c89dcdd2f",
    "description": "Returns a single article",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Advisors",
      "item": [
        {
          "id": "6e48f68f-6853-4a30-8b38-c8a137fdebaa",
          "name": "findAdvisorByID",
          "request": {
            "url": {
              "protocol": "http",
              "host": "staging.vestorly.com",
              "path": [
                "api",
                "v2",
                "advisors/:id"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "vestorly-auth",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "vestorly_auth",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns a single advisor given their ID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a75d120-d13a-4847-856d-6b0a0f3cf5de"
            }
          ]
        }
      ]
    },
    {
      "name": "Articles",
      "item": [
        {
          "id": "b6aa0bb3-d5ed-495c-b338-dbfac614c434",
          "name": "findArticles",
          "request": {
            "url": "http://staging.vestorly.com/api/v2/articles?access_token=%7B%7D&limit=%7B%7D&sort_by=%7B%7D&sort_direction=%7B%7D&text_query=%7B%7D&vestorly-auth=%7B%7D&vestorly_auth=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns all articles"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "07e9bae5-74f3-49ed-a9aa-9cb48b6eec79"
            }
          ]
        },
        {
          "id": "3b78a244-6ee4-4f9f-a7ea-079575c8d7d1",
          "name": "findArticleByID",
          "request": {
            "url": {
              "protocol": "http",
              "host": "staging.vestorly.com",
              "path": [
                "api",
                "v2",
                "articles/:id"
              ],
              "query": [
                {
                  "key": "access_token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "vestorly-auth",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "vestorly_auth",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns a single article"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1899cf21-9697-47e9-a27b-e39c0f8ed8de"
            }
          ]
        }
      ]
    }
  ]
}