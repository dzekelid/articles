{
  "info": {
    "name": "reverb Get Articles",
    "_postman_id": "a61de2bd-a3a9-4da1-a182-cbf5d200134d",
    "description": "Get articles.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Articles",
      "item": [
        {
          "id": "dfc79fca-d817-4b15-a586-1a2fce73fbb7",
          "name": "getArticles",
          "request": {
            "url": "http://api.reverb.com/api/articles?exclude_featured=%7B%7D&offset=%7B%7D&page=%7B%7D&per_page=%7B%7D&query=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get articles."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7cba6aba-5039-45f0-aae9-50ed61f21a57"
            }
          ]
        }
      ]
    }
  ]
}