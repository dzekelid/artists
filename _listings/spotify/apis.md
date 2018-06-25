---
name: Spotify
x-slug: spotify
description: Spotify is a digital music service that gives you access to millions
  of songs.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
x-kinRank: "8"
x-alexaRank: "132"
tags: Artists
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/spotify/apis.md
specificationVersion: "0.14"
apis:
- name: Spotify Get Artists
  x-api-slug: spotify
  description: '[Get Several Artists](https://developer.spotify.com/web-api/get-several-artists/)'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//artists
  tags: Music,Artists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/spotify/artists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/spotify/artists-get-openapi.md
- name: Spotify Get Artist
  x-api-slug: spotify
  description: '[Get an Artist](https://developer.spotify.com/web-api/get-artist/)'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//artists/{id}
  tags: Music,Artists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/spotify/artistsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/spotify/artistsid-get-openapi.md
- name: Spotify Get Artist Albums
  x-api-slug: spotify
  description: '[Get an Artist''s Albums](https://developer.spotify.com/web-api/get-artists-albums/)'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//artists/{id}/albums
  tags: Music,Artists,Albums
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/spotify/artistsidalbums-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/spotify/artistsidalbums-get-openapi.md
- name: Spotify Get Artist Related ARtists
  x-api-slug: spotify
  description: '[Get an Artist''s Related Artists](https://developer.spotify.com/web-api/get-related-artists/)'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//artists/{id}/related-artists
  tags: Music,Artists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/spotify/artistsidrelatedartists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/spotify/artistsidrelatedartists-get-openapi.md
- name: Spotify Get Artist Top Tracks
  x-api-slug: spotify
  description: '[Get an Artist''s Top Tracks](https://developer.spotify.com/web-api/get-artists-top-tracks/)'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//artists/{id}/top-tracks
  tags: Music,Artists,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/spotify/artistsidtoptracks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/spotify/artistsidtoptracks-get-openapi.md
- name: Spotify
  x-api-slug: spotify
  description: Spotify is a digital music service that gives you access to millions
    of songs.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1
  tags: Artists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artists/master/_listings/spotify/openapi.md
x-common:
- type: x-api-json--authoritative
  url: https://developer.spotify.com/wp-content/uploads/apis.json
- type: x-android-sdk
  url: https://developer.spotify.com/technologies/spotify-android-sdk/
- type: x-application-gallery
  url: https://developer.spotify.com/my-applications/
- type: x-application-gallery
  url: https://developer.spotify.com/showcase/
- type: x-base-url
  url: https://api.spotify.com
- type: x-blog
  url: http://www.spotify.com/blog/
- type: x-blog-rss
  url: http://www.spotify.com/blog/feed
- type: x-change-log
  url: https://developer.spotify.com/web-api/change-log/
- type: x-console
  url: https://developer.spotify.com/web-api/console/
- type: x-crunchbase
  url: https://crunchbase.com/organization/spotify
- type: x-crunchbase
  url: http://www.crunchbase.com/company/spotify
- type: x-developer
  url: https://developer.spotify.com/
- type: x-email
  url: office@spotify.com
- type: x-ios-sdk
  url: https://developer.spotify.com/technologies/spotify-ios-sdk/
- type: x-issues
  url: https://github.com/spotify/web-api/issues
- type: x-linkedin
  url: https://www.linkedin.com/company/spotify/
- type: x-stack-overflow
  url: http://stackoverflow.com/questions/tagged/spotify
- type: x-terms-of-service
  url: https://developer.spotify.com/developer-terms-of-use/
- type: x-twitter
  url: https://twitter.com/SpotifyPlatform
- type: x-twitter
  url: https://twitter.com/spotify
- type: x-github
  url: https://github.com/spotify
- type: x-website
  url: http://www.spotify.com
- type: x-website
  url: http://spotify.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---