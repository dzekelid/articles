{
  "info": {
    "name": "Kentico Cloud Order articles by publish date",
    "_postman_id": "a209cb91-82d2-4a67-b4af-a8e790048ecb",
    "description": "Filter the content items by content type by including the `order` query parameter and a content element codename.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Order",
      "item": [
        {
          "id": "e2be4f82-a3a1-4e18-8205-8a3d4acae824",
          "name": "975bf280Fd91488c994c2f04416e5ee3ItemsGet8",
          "request": {
            "url": "http://deliver.kenticocloud.com/975bf280-fd91-488c-994c-2f04416e5ee3/items?order=%7B%7D&system.type=%7B%7D",
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
            "description": "Filter the content items by content type by including the `order` query parameter and a content element codename."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "163de037-6198-49ac-ab23-e4019da4abde"
            }
          ]
        }
      ]
    }
  ]
}