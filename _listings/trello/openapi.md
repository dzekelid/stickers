swagger: "2.0"
x-collection-name: Trello
x-complete: 1
info:
  title: Trello
  description: this-document-describes-the-rest-api-of-trello-as-published-by-trello-com---a-hrefhttpstrello-comdocsindex-html-target-blankofficial-documentationa--a-hrefhttpstrello-comdocsapi-target-blankthe-html-pages-that-were-scraped-in-order-to-generate-this-specification-a
  termsOfService: https://trello.com/legal
  contact:
    name: Trello
    url: https://trello.com/home
  version: "1.0"
host: trello.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /cards/{idCard}/stickers:
    get:
      summary: Get Cards Stickers
      description: Get cards stickers.
      operationId: getCardsStickersByIdCard
      x-api-path-slug: cardsidcardstickers-get
      parameters:
      - in: query
        name: fields
        description: 'all or a comma-separated list of: image, imageScaled, imageUrl,
          left, rotate, top or zIndex'
      - in: path
        name: idCard
        description: card id or shortlink
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        100:
          description: Invalid API Key - The API key passed was not valid or has expired
        105:
          description: Service currently unavailable - The requested service is temporarily
            unavailable
        106:
          description: Write operation failed - The requested operation failed due
            to a temporary issue
        111:
          description: Format "xxx" not found - The requested response format was
            not found
        112:
          description: Method "xxx" not found - The requested method was not found
        114:
          description: Invalid SOAP envelope - The SOAP envelope send in the request
            could not be parsed
        115:
          description: Invalid XML-RPC Method Call - The XML-RPC request document
            could not be parsed
        116:
          description: Bad URL found - One or more arguments contained a URL that
            has been used for abuse on Flickr
        200:
          description: OK
      tags:
      - Cards
      - Stickers
    post:
      summary: Post Cards Stickers
      description: Post cards stickers.
      operationId: addCardsStickersByIdCard
      x-api-path-slug: cardsidcardstickers-post
      parameters:
      - in: body
        name: body
        description: Attributes of Cards Stickers to be added
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idCard
        description: card id or shortlink
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Cards
      - Stickers
  /cards/{idCard}/stickers/{idSticker}:
    delete:
      summary: Delete Cards Stickers Sticker
      description: Delete cards stickers sticker.
      operationId: deleteCardsStickersByIdCardByIdSticker
      x-api-path-slug: cardsidcardstickersidsticker-delete
      parameters:
      - in: path
        name: idCard
        description: card id or shortlink
      - in: path
        name: idSticker
        description: idSticker
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Cards
      - Stickers
      - Sticker
    get:
      summary: Get Cards Stickers Sticker
      description: Get cards stickers sticker.
      operationId: getCardsStickersByIdCardByIdSticker
      x-api-path-slug: cardsidcardstickersidsticker-get
      parameters:
      - in: query
        name: fields
        description: 'all or a comma-separated list of: image, imageScaled, imageUrl,
          left, rotate, top or zIndex'
      - in: path
        name: idCard
        description: card id or shortlink
      - in: path
        name: idSticker
        description: idSticker
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Cards
      - Stickers
      - Sticker
    put:
      summary: Put Cards Stickers Sticker
      description: Put cards stickers sticker.
      operationId: updateCardsStickersByIdCardByIdSticker
      x-api-path-slug: cardsidcardstickersidsticker-put
      parameters:
      - in: body
        name: body
        description: Attributes of Cards Stickers to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: idCard
        description: card id or shortlink
      - in: path
        name: idSticker
        description: idSticker
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Cards
      - Stickers
      - Sticker