---
name: Getty Images
x-slug: getty-images
description: Find high resolution royalty-free images, editorial stock photos, vector
  art, video footage clips and stock music licensing at the richest image search photo
  library online.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1013-getty-images.jpg
x-kinRank: "8"
x-alexaRank: "1939"
tags: Artists
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/getty-images/apis.md
specificationVersion: "0.14"
apis:
- name: Getty Images Search Artist Images
  x-api-slug: getty-images
  description: Search for images by a photographer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1013-getty-images.jpg
  humanURL: http://www.gettyimages.com/
  baseURL: https://api.gettyimages.com////v3/artists/images
  tags: Images,Artists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/getty-images/v3artistsimages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/getty-images/v3artistsimages-get-openapi.md
- name: Getty Images Search Artist ImaVideosges
  x-api-slug: getty-images
  description: Search for videos by a photographer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1013-getty-images.jpg
  humanURL: http://www.gettyimages.com/
  baseURL: https://api.gettyimages.com////v3/artists/videos
  tags: Images,Artists,Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/getty-images/v3artistsvideos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/getty-images/v3artistsvideos-get-openapi.md
- name: Getty Images
  x-api-slug: getty-images
  description: Find high resolution royalty-free images, editorial stock photos, vector
    art, video footage clips and stock music licensing at the richest image search
    photo library online.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1013-getty-images.jpg
  humanURL: http://www.gettyimages.com/
  baseURL: https://api.gettyimages.com//
  tags: Artists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/getty-images/openapi.md
x-common:
- type: x-authentication
  url: https://github.com/gettyimages/connect#authentication
- type: x-base
  url: https://connect.gettyimages.com/
- type: x--net-sdk
  url: https://github.com/gettyimages/connect_sdk_csharp
- type: x-crunchbase
  url: https://crunchbase.com/organization/gettyimages
- type: x-crunchbase
  url: http://www.crunchbase.com/company/ge-tt
- type: x-developer
  url: http://api.gettyimages.com/
- type: x-documentation
  url: https://api.gettyimages.com/swagger/ui/index.html
- type: x-email
  url: privacy@gettyimages.com
- type: x-email
  url: sales@gettyimages.com
- type: x-email
  url: copyright@gettyimages.com
- type: x-embeddable
  url: https://github.com/gettyimages/connect#oembed
- type: x-forum
  url: http://api.gettyimages.com/forum
- type: x-getting-started
  url: https://github.com/gettyimages/connect#getting-started
- type: x-github
  url: https://github.com/gettyimages
- type: x-java-sdk
  url: https://github.com/gettyimages/connect_sdk_java
- type: x-node-js-sdk
  url: https://github.com/gettyimages/connect_sdk_nodejs
- type: x-objectivec-sdk
  url: https://github.com/gettyimages/connect_sdk_objective-c
- type: x-php-sdk
  url: https://github.com/gettyimages/connect_sdk_php
- type: x-pricing
  url: http://www.gettyimages.com/subscribe
- type: x-ruby-sdk
  url: https://github.com/gettyimages/connect_sdk_ruby
- type: x-twitter
  url: https://twitter.com/GettyImages
- type: x-website
  url: http://www.gettyimages.com/
- type: x-website
  url: http://gettyimages.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---