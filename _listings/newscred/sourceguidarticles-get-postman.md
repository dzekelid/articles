{
  "info": {
    "name": "News Cred Source Articles",
    "_postman_id": "1d07d309-94f0-4c79-a619-b0f230e8a29d",
    "description": "Returns a list of articles provided by the specified source",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "d6b65c92-41f2-42e4-8ac1-ba91836323b1",
          "name": "getTopicGu]Articles",
          "request": {
            "url": "http://api.newscred.com/topic/{guid]/articles/?access_key=%7B%7D&article_filter_mode=%7B%7D&article_filter_name=%7B%7D&categories=%7B%7D&from_date=%7B%7D&get_topics=%7B%7D&guid=%7B%7D&has_images=%7B%7D&languages=%7B%7D&licensed=%7B%7D&media_types=%7B%7D&offset=%7B%7D&pagesize=%7B%7D&sort=%7B%7D&sources=%7B%7D&source_countries=%7B%7D&source_filter_mode=%7B%7D&source_filter_name=%7B%7D&to_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of articles related to the specified topic."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab6a071e-f008-4173-b7d5-b98e7ed6c663"
            }
          ]
        },
        {
          "id": "b2520da5-67ea-40ed-bf4b-330fb304d563",
          "name": "getArticles",
          "request": {
            "url": "http://api.newscred.com/articles/?access_key=%7B%7D&article_filter_mode=%7B%7D&article_filter_name=%7B%7D&boolean_operator=%7B%7D&categories=%7B%7D&exact=%7B%7D&from_date=%7B%7D&get_topics=%7B%7D&has_images=%7B%7D&languages=%7B%7D&licensed=%7B%7D&links=%7B%7D&max_length=%7B%7D&media_types=%7B%7D&min_length=%7B%7D&mm=%7B%7D&modified_since=%7B%7D&offset=%7B%7D&query=%7B%7D&query_fields=%7B%7D&safe_search=%7B%7D&sort=%7B%7D&sources=%7B%7D&source_countries=%7B%7D&source_filter_mode=%7B%7D&source_filter_name=%7B%7D&topics=%7B%7D&topic_filter_mode=%7B%7D&topic_filter_name=%7B%7D&to_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of articles according to the specified set of parameters."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36f94b1e-89b8-456f-8b02-876506b86ce2"
            }
          ]
        },
        {
          "id": "2577fea1-cd4a-41d3-8fe4-1103b5affca0",
          "name": "getAuthorGuArticles",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "author/:guid/articles/"
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
                  "key": "categories",
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
                  "key": "topics",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_name",
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
                  "id": "guid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns articles written by the specified author and matching the given query string."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f4bd33b-1102-498d-befb-c034abb843ea"
            }
          ]
        },
        {
          "id": "2bbaa4eb-55fd-40ce-bce5-e0cc4676e391",
          "name": "getAuthorGuTopics",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "author/:guid/topics/"
              ],
              "query": [
                {
                  "key": "access_key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "from_date",
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
                  "key": "topics",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_classifications",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_subclassifications",
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
                  "id": "guid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of topics related to an author."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e2e00493-b669-414d-9137-63906ae5aa9f"
            }
          ]
        },
        {
          "id": "7b80ae6e-b99c-430f-a993-f0a6cd0332d1",
          "name": "getCategories",
          "request": {
            "url": "http://api.newscred.com/categories/?access_key=%7B%7D&autosuggest=%7B%7D&query=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Search for categories"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab685428-71f6-4bd8-9e89-3d02f528a229"
            }
          ]
        },
        {
          "id": "ceeb0fa1-853b-45bb-a179-b3f3d10df086",
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
              "id": "d0fdb167-aea8-4d6e-bff0-b0b5b48de92c"
            }
          ]
        },
        {
          "id": "9c530941-dd6d-4257-9ac2-bb72371021b9",
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
              "id": "8f96f096-7274-4076-96d3-b01c7b37b18e"
            }
          ]
        },
        {
          "id": "a3574af3-91c7-4d6a-9a1a-9f06d6a4bf30",
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
              "id": "057a295f-1ee4-4d1e-ba63-d057ba7f9bb6"
            }
          ]
        },
        {
          "id": "9853e1fa-e03d-4b81-82d3-02dfaa560908",
          "name": "getCategoryDashedNameImages",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "category/:dashed-name/images/"
              ],
              "query": [
                {
                  "key": "access_key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "safe_search",
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
            "description": "Gets images related to the specified category."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "269cc3c1-c021-4b5a-8aa4-358d54b919f3"
            }
          ]
        },
        {
          "id": "79b4110a-39b3-440c-92d8-2356391b8497",
          "name": "getSourceGuArticles",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.newscred.com",
              "path": [
                "source/:GUID/articles/"
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
                  "key": "categories",
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
                  "key": "topics",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_mode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "topic_filter_name",
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
                  "id": "GUID",
                  "value": "GUID",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of articles provided by the specified source"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e46a08eb-ca50-446e-a16a-873a2880ac2e"
            }
          ]
        }
      ]
    }
  ]
}