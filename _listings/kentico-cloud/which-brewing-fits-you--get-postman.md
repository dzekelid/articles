{
  "info": {
    "name": "Kentico Cloud Previewing an article",
    "_postman_id": "dda92763-6fbf-4cd4-b8cb-3dbac4ccd264",
    "description": "Preview a specific content item.\n\nSee <https://developer.kenticocloud.com/docs/preview-content-via-api> for details.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Order",
      "item": [
        {
          "id": "49be826b-3f8d-4afa-9b6b-69f18cb8f1e1",
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
              "id": "860e57b4-9b56-43d2-922c-ac3da2bbc363"
            }
          ]
        }
      ]
    },
    {
      "name": "Previewing",
      "item": [
        {
          "id": "0c2e46ac-3858-40aa-8a7e-d4d4737cf2e1",
          "name": "WhichBrewingFitsYouGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/which_brewing_fits_you_",
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
            "description": "Preview a specific content item.\n\nSee <https://developer.kenticocloud.com/docs/preview-content-via-api> for details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04890f03-e7c7-47df-87ba-9ebb762ea18d"
            }
          ]
        }
      ]
    }
  ]
}