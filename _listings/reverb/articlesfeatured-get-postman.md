{
  "info": {
    "name": "reverb Get Articles Featured",
    "_postman_id": "62df91a4-007d-4fe1-8cdc-cdfd3ad16d3c",
    "description": "See featured Reverb blog posts",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Articles",
      "item": [
        {
          "id": "daa942fc-ff77-4281-a2d5-ef02fe9cd767",
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
              "id": "d4ff0ec4-8d4c-4d78-b087-2d7bb752a4dc"
            }
          ]
        }
      ]
    }
  ]
}