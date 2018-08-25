{
  "info": {
    "name": "News Cred Topic Articles",
    "_postman_id": "c92cebef-51cc-47bf-a663-f0fd7872a065",
    "description": "Returns a list of articles related to the specified topic.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "News",
      "item": [
        {
          "id": "e98c78b5-8aff-42e6-8cb4-8b5855e89689",
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
              "id": "b9f79ca2-ece8-44bb-b988-f5cf975846de"
            }
          ]
        }
      ]
    }
  ]
}