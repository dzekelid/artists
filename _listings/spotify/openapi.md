swagger: "2.0"
x-collection-name: Spotify
x-complete: 1
info:
  title: Spotify
  description: our-web-api-lets-your-applications-fetch-data-from-the-spotify-music-catalog-and-manage-users-playlists-and-saved-music--based-on-simple-rest-principles-our-web-api-endpoints-return-metadata-in-json-format-about-artists-albums-and-tracks-directly-from-the-spotify-catalogue--the-api-also-provides-access-to-userrelated-data-such-as-playlists-and-music-saved-in-a-your-music-library-subject-to-users-authorization-
  version: v1
host: api.spotify.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /artists:
    get:
      summary: Get Artists
      description: '[Get Several Artists](https://developer.spotify.com/web-api/get-several-artists/)'
      operationId: get-several-artistshttpsdeveloperspotifycomwebapigetseveralartists
      x-api-path-slug: artists-get
      parameters:
      - in: query
        name: ids
        description: A comma-separated list of IDs
      responses:
        200:
          description: OK
      tags:
      - Music
      - Artists
  /artists/{id}:
    get:
      summary: Get Artist
      description: '[Get an Artist](https://developer.spotify.com/web-api/get-artist/)'
      operationId: get-an-artisthttpsdeveloperspotifycomwebapigetartist
      x-api-path-slug: artistsid-get
      parameters:
      - in: path
        name: id
        description: The Spotify ID for the artist
      responses:
        200:
          description: OK
      tags:
      - Music
      - Artists
  /artists/{id}/albums:
    get:
      summary: Get Artist Albums
      description: '[Get an Artist''s Albums](https://developer.spotify.com/web-api/get-artists-albums/)'
      operationId: get-an-artists-albumshttpsdeveloperspotifycomwebapigetartistsalbums
      x-api-path-slug: artistsidalbums-get
      parameters:
      - in: query
        name: album_type
        description: Filter by album types
      - in: path
        name: id
        description: The Spotify ID for the artist
      - in: query
        name: limit
        description: The maximum number of items to return
      - in: query
        name: market
        description: The market (an ISO 3166-1 alpha-2 country code)
      - in: query
        name: offset
        description: The index of the first item to return
      responses:
        200:
          description: OK
      tags:
      - Music
      - Artists
      - Albums
  /artists/{id}/related-artists:
    get:
      summary: Get Artist Related ARtists
      description: '[Get an Artist''s Related Artists](https://developer.spotify.com/web-api/get-related-artists/)'
      operationId: get-an-artists-related-artistshttpsdeveloperspotifycomwebapigetrelatedartists
      x-api-path-slug: artistsidrelatedartists-get
      parameters:
      - in: path
        name: id
        description: The Spotify ID for the artist
      responses:
        200:
          description: OK
      tags:
      - Music
      - Artists
  /artists/{id}/top-tracks:
    get:
      summary: Get Artist Top Tracks
      description: '[Get an Artist''s Top Tracks](https://developer.spotify.com/web-api/get-artists-top-tracks/)'
      operationId: get-an-artists-top-trackshttpsdeveloperspotifycomwebapigetartiststoptracks
      x-api-path-slug: artistsidtoptracks-get
      parameters:
      - in: query
        name: country
        description: The country (an ISO 3166-1 alpha-2 country code)
      - in: path
        name: id
        description: The Spotify ID for the artist
      responses:
        200:
          description: OK
      tags:
      - Music
      - Artists
      - Tracks