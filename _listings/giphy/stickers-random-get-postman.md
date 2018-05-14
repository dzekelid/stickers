{
  "info": {
    "name": "Giphy Gif API Random Sticker",
    "_postman_id": "29357af8-9405-4af0-a41b-ef76e388aa14",
    "description": "Returns a random GIF, limited by tag. Excluding the tag parameter will return a random GIF from the GIPHY catalog.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "stickers",
      "item": [
        {
          "id": "3b72f5cb-59e8-4365-9959-c0afb1f49c38",
          "name": "randomSticker",
          "request": {
            "url": "http://api.giphy.com/v1/stickers/random?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a random GIF, limited by tag"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb19d203-7452-4b06-abcb-3b74206b1f08"
            }
          ]
        }
      ]
    }
  ]
}