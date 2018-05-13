{
  "info": {
    "name": "Healthcare",
    "_postman_id": "70d48cae-6e45-4a7d-ae6e-719ead3ae347",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "insurance",
      "item": [
        {
          "id": "773f40bf-7a90-4b1a-878d-1db1acfa10c7",
          "name": "returns-pages-content",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.healthcare.gov",
              "path": [
                "api/articles:mediaTypeExtension"
              ],
              "variable": [
                {
                  "id": "mediaTypeExtension",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns pages content"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "739dd809-3b32-4875-be6d-b24e7fc9baec"
            }
          ]
        }
      ]
    }
  ]
}