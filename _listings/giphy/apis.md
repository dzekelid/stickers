---
name: Giphy
x-slug: giphy
description: Giphy is a search engine for GIFs. Animated GIFs have existed for decades,
  but there was still no good way to browse and discover the best the web had to offer.
  And the vision for Giphy isn&rsquo;t really just about finding GIFs. It&rsquo;s
  a search engine today but soon you&rsquo;ll see it grow into a community, a platform
  with a host of features targeted at gif artists, enthusiasts, bloggers, and anyone
  generally looking to discover or create that next big meme.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Stickers
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/stickers/master/_listings/giphy/apis.md
specificationVersion: "0.14"
apis:
- name: Giphy - Random Sticker
  x-api-slug: stickersrandom-get
  description: Returns a random GIF, limited by tag. Excluding the tag parameter will
    return a random GIF from the GIPHY catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
  humanURL: https://giphy.com
  baseURL: http://api.giphy.com//v1
  tags: Images, Gifs, Indie EdTech Data Jam, Stack Network, API Provider, Profiles,
    General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stickers/master/_listings/giphy/stickersrandom-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stickers/master/_listings/giphy/stickersrandom-get-openapi.md
- name: Giphy - Search Stickers
  x-api-slug: stickerssearch-get
  description: Replicates the functionality and requirements of the classic GIPHY
    search, but returns animated stickers rather than GIFs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
  humanURL: https://giphy.com
  baseURL: http://api.giphy.com//v1
  tags: Images, Gifs, Indie EdTech Data Jam, Stack Network, API Provider, Profiles,
    General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stickers/master/_listings/giphy/stickerssearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stickers/master/_listings/giphy/stickerssearch-get-openapi.md
- name: Giphy - Translate phrase to Sticker
  x-api-slug: stickerstranslate-get
  description: The translate API draws on search, but uses the GIPHY `special sauce`
    to handle translating from one vocabulary to another. In this case, words and
    phrases to GIFs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
  humanURL: https://giphy.com
  baseURL: http://api.giphy.com//v1
  tags: Images, Gifs, Indie EdTech Data Jam, Stack Network, API Provider, Profiles,
    General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stickers/master/_listings/giphy/stickerstranslate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stickers/master/_listings/giphy/stickerstranslate-get-openapi.md
- name: Giphy - Trending Stickers
  x-api-slug: stickerstrending-get
  description: Fetch Stickers currently trending online. Hand curated by the GIPHY
    editorial team. Returns 25 results by default.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/giphy-logo.png
  humanURL: https://giphy.com
  baseURL: http://api.giphy.com//v1
  tags: Images, Gifs, Indie EdTech Data Jam, Stack Network, API Provider, Profiles,
    General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stickers/master/_listings/giphy/stickerstrending-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stickers/master/_listings/giphy/stickerstrending-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://gig..crowd.api.gallery.streamdata.io
- type: x-api-stack
  url: http://giphy.stack.network
- type: x-blog
  url: http://blog.giphy.com/
- type: x-developer
  url: https://api.giphy.com/
- type: x-github
  url: https://github.com/Giphy
- type: x-twitter
  url: https://twitter.com/giphy
- type: x-website
  url: https://giphy.com
- type: x-website
  url: http://giphy.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---