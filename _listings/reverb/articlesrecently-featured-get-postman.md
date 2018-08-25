{
  "info": {
    "name": "reverb Get Articles Recently Featured",
    "_postman_id": "913d4a00-db4d-4fe0-882d-2c97b66888c3",
    "description": "Get articles recently featured.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Articles",
      "item": [
        {
          "id": "675a097b-80de-4f8b-aaf2-4baceeb81a6b",
          "name": "getArticlesFeatured",
          "request": {
            "url": "http://api.reverb.com/api/articles/featured",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "See featured Reverb blog posts"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e9d45ec-2c47-48f3-9fe0-fd1642d838c5"
            }
          ]
        },
        {
          "id": "612b3aee-5c5f-4381-8fdb-09afa5d73f08",
          "name": "getArticlesRecentlyFeatured",
          "request": {
            "url": "http://api.reverb.com/api/articles/recently_featured",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get articles recently featured."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "61e73582-765b-4516-8363-8990a5fe03f9"
            }
          ]
        }
      ]
    }
  ]
}