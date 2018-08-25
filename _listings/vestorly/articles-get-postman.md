{
  "info": {
    "name": "Vestorly Get Articles",
    "_postman_id": "8c9a1201-b603-4745-9ea0-cab584b93460",
    "description": "Returns all articles",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Advisors",
      "item": [
        {
          "id": "390e908a-ec0b-4f4c-ae43-12f474560570",
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
              "id": "d422e640-7d62-4e0e-bed2-32dd8e346fa6"
            }
          ]
        }
      ]
    },
    {
      "name": "Articles",
      "item": [
        {
          "id": "9cab57d3-1ed1-42f8-8ad6-ac2f30e47ab5",
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
              "id": "0b870164-7d9f-4f0b-8eeb-42b0b6da00f7"
            }
          ]
        }
      ]
    }
  ]
}