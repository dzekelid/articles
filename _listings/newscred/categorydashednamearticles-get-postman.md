{
  "info": {
    "name": "News Cred Category Articles",
    "_postman_id": "df847abe-2add-4e27-8d0d-0a387a62fd41",
    "description": "Search for articles within the category specified by dashed name.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "80d3dd9d-bda0-41e3-848a-aa1cac9e6761",
          "name": "getCategoryDashedNameSources",
          "request": {
            "url": "http://api.newscred.com/category/dashed-name/sources/?access_key=%7B%7D&from_date=%7B%7D&media_types=%7B%7D&offset=%7B%7D&pagesize=%7B%7D&sources=%7B%7D&source_countries=%7B%7D&source_filter_mode=%7B%7D&source_filter_name=%7B%7D&to_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of sources that write most frequently about the category specified by the dashed name"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e0313607-b95c-4558-923f-d66e8a8db132"
            }
          ]
        },
        {
          "id": "b92bc3cf-1928-4150-a2a7-1e695968924b",
          "name": "getCategoryDashedNameTopics",
          "request": {
            "url": "http://api.newscred.com/category/dashed-name/topics/?access_key=%7B%7D&from_date=%7B%7D&offset=%7B%7D&pagesize=%7B%7D&topic_classifications=%7B%7D&topic_filter_mode=%7B%7D&topic_filter_name=%7B%7D&topic_subclassifications=%7B%7D&to_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of topics within the category specified by the dashed name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df78fafc-d6c2-406d-b75e-f80032aa0fb3"
            }
          ]
        },
        {
          "id": "ddb0120e-e2eb-4e17-9841-f38cc7ede736",
          "name": "getCategoryCategoryName]Stories",
          "request": {
            "url": "http://api.newscred.com/category/{category-name]/stories/?access_key=%7B%7D&article_filter_mode=%7B%7D&article_filter_name=%7B%7D&cluster_size=%7B%7D&from_date=%7B%7D&get_topics=%7B%7D&has_images=%7B%7D&languages=%7B%7D&licensed=%7B%7D&media_types=%7B%7D&offset=%7B%7D&pagesize=%7B%7D&sources=%7B%7D&source_countries=%7B%7D&source_filter_mode=%7B%7D&source_filter_name=%7B%7D&to_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Find the top news stories related to a given category. A story is a collection of similar articles."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "14aacb98-a28f-47b0-b255-f5443d9d04bb"
            }
          ]
        }
      ]
    },
    {
      "name": "Category",
      "item": [
        {
          "id": "02197946-e318-4078-994b-6ec29633be58",
          "name": "getCategoryDashedNameArticles",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "category/:dashed-name/articles/"
              ],
              "query": [
                {
                  "key": "access_key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "article_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "article_filter_name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "from_date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "get_topics",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "has_images",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "languages",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "licensed",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "media_types",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pagesize",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sort",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sources",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "source_countries",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "source_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "source_filter_name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "to_date",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "dashed-name",
                  "value": "dashed-name",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Search for articles within the category specified by dashed name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "709e22b0-1d6e-4d5c-8f8a-eaebba500ec5"
            }
          ]
        }
      ]
    }
  ]
}