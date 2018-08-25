---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Get Gigme Artist Events Past
  version: 1.0.0
  description: Get gigme artist events past.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/manager/artists:
    get:
      summary: Get Manager Artists
      description: Get manager artists.
      operationId: getApiV1ManagerArtists
      x-api-path-slug: apiv1managerartists-get
      parameters:
      - in: header
        name: Authorization
      - in: query
        name: page
        description: The page number
      - in: query
        name: request.query
      responses:
        200:
          description: OK
      tags:
      - Manager
      - Artists
  /api/v1/manager/artists/{artistId}:
    delete:
      summary: Delete Manager Artists Artistid
      description: Delete manager artists artistid.
      operationId: deleteApiV1ManagerArtistsArtist
      x-api-path-slug: apiv1managerartistsartistid-delete
      parameters:
      - in: path
        name: artistId
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Manager
      - Artists
      - Artistid
  /api/v1/notify/artists:
    get:
      summary: Get Notify Artists
      description: Get notify artists.
      operationId: getApiV1NotifyArtists
      x-api-path-slug: apiv1notifyartists-get
      responses:
        200:
          description: OK
      tags:
      - Notify
      - Artists
  /api/v1/notify/artists/new:
    get:
      summary: Get Notify Artists New
      description: Get notify artists new.
      operationId: getApiV1NotifyArtistsNew
      x-api-path-slug: apiv1notifyartistsnew-get
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Notify
      - Artists
      - New
  /api/v1/rating/artists:
    post:
      summary: Post Rating Artists
      description: Post rating artists.
      operationId: postApiV1RatingArtists
      x-api-path-slug: apiv1ratingartists-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Rating
      - Artists
  /api/v1/rating/{eventId}/artists:
    get:
      summary: Get Rating Eventid Artists
      description: Get rating eventid artists.
      operationId: getApiV1RatingEventArtists
      x-api-path-slug: apiv1ratingeventidartists-get
      parameters:
      - in: path
        name: eventId
      responses:
        200:
          description: OK
      tags:
      - Rating
      - Eventid
      - Artists
  /api/v1/gigme/artist/search/{page}:
    post:
      summary: Post Gigme Artist Search Page
      description: Post gigme artist search page.
      operationId: postApiV1GigmeArtistSearchPage
      x-api-path-slug: apiv1gigmeartistsearchpage-post
      parameters:
      - in: path
        name: page
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Artist
      - Search
      - Page
  /api/v1/gigme/artist/searchActive:
    post:
      summary: Post Gigme Artist Searchactive
      description: Post gigme artist searchactive.
      operationId: postApiV1GigmeArtistSearchactive
      x-api-path-slug: apiv1gigmeartistsearchactive-post
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Artist
      - Searchactive
  /api/v1/gigme/artist:
    get:
      summary: Get Gigme Artist
      description: Get gigme artist.
      operationId: getApiV1GigmeArtist
      x-api-path-slug: apiv1gigmeartist-get
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Artist
  /api/v1/gigme/artist/{unique}/details:
    get:
      summary: Get Gigme Artist Unique Details
      description: Get gigme artist unique details.
      operationId: getApiV1GigmeArtistUniqueDetails
      x-api-path-slug: apiv1gigmeartistuniquedetails-get
      parameters:
      - in: path
        name: unique
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Artist
      - Unique
      - Details
  /api/v1/gigme/artist/{id}/videos:
    get:
      summary: Get Gigme Artist Veos
      description: Get gigme artist veos.
      operationId: getApiV1GigmeArtistVeos
      x-api-path-slug: apiv1gigmeartistidvideos-get
      parameters:
      - in: path
        name: id
        description: Id
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Artist
      - Veos
  /api/v1/gigme/artist/{id}/events/past:
    get:
      summary: Get Gigme Artist Events Past
      description: Get gigme artist events past.
      operationId: getApiV1GigmeArtistEventsPast
      x-api-path-slug: apiv1gigmeartistideventspast-get
      parameters:
      - in: path
        name: id
        description: Id
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Artist
      - Events
      - Past
  /api/v1/gigme/artist/{id}/events/future:
    get:
      summary: Get Gigme Artist Events Future
      description: Get gigme artist events future.
      operationId: getApiV1GigmeArtistEventsFuture
      x-api-path-slug: apiv1gigmeartistideventsfuture-get
      parameters:
      - in: path
        name: id
        description: Id
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Artist
      - Events
      - Future
  /api/v1/art/invited/{artistId}/{eventId}:
    get:
      summary: Get Art Invited Artistid Eventid
      description: Get art invited artistid eventid.
      operationId: getApiV1ArtInvitedArtistEvent
      x-api-path-slug: apiv1artinvitedartistideventid-get
      parameters:
      - in: path
        name: artistId
      - in: path
        name: eventId
      responses:
        200:
          description: OK
      tags:
      - Art
      - Invited
      - Artistid
      - Eventid
  /api/v1/managers/accept/{artistId}:
    post:
      summary: Post Managers Accept Artistid
      description: Post managers accept artistid.
      operationId: postApiV1ManagersAcceptArtist
      x-api-path-slug: apiv1managersacceptartistid-post
      parameters:
      - in: path
        name: artistId
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Managers
      - Accept
      - Artistid
  /api/v1/managers/approve/{artistId}:
    post:
      summary: Post Managers Approve Artistid
      description: Post managers approve artistid.
      operationId: postApiV1ManagersApproveArtist
      x-api-path-slug: apiv1managersapproveartistid-post
      parameters:
      - in: path
        name: artistId
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Managers
      - Approve
      - Artistid
  /api/v1/managers/reject/{artistId}/{reason}:
    post:
      summary: Post Managers Reject Artistid Reason
      description: Post managers reject artistid reason.
      operationId: postApiV1ManagersRejectArtistReason
      x-api-path-slug: apiv1managersrejectartistidreason-post
      parameters:
      - in: path
        name: artistId
      - in: header
        name: Authorization
      - in: path
        name: reason
      responses:
        200:
          description: OK
      tags:
      - Managers
      - Reject
      - Artistid
      - Reason
  /api/v1/request/{requestId}/art/{artistId}/rider:
    get:
      summary: Get Request Requestid Art Artistid Rer
      description: Get request requestid art artistid rer.
      operationId: getApiV1RequestRequestArtArtistRer
      x-api-path-slug: apiv1requestrequestidartartistidrider-get
      parameters:
      - in: path
        name: artistId
      - in: header
        name: Authorization
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Art
      - Artistid
      - Rer
  /api/v1/request/{requestId}/art/{artistId}/rider/home:
    get:
      summary: Get Request Requestid Art Artistid Rer Home
      description: Get request requestid art artistid rer home.
      operationId: getApiV1RequestRequestArtArtistRerHome
      x-api-path-slug: apiv1requestrequestidartartistidriderhome-get
      parameters:
      - in: path
        name: artistId
      - in: header
        name: Authorization
      - in: path
        name: requestId
        description: /
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Art
      - Artistid
      - Rer
      - Home
  /api/v1/request/{requestId}/art/{artistId}/presskit/{photoId}:
    get:
      summary: Get Request Requestid Art Artistid Presskit Photoid
      description: Get request requestid art artistid presskit photoid.
      operationId: getApiV1RequestRequestArtArtistPresskitPhoto
      x-api-path-slug: apiv1requestrequestidartartistidpresskitphotoid-get
      parameters:
      - in: path
        name: artistId
      - in: header
        name: Authorization
      - in: path
        name: photoId
      - in: path
        name: requestId
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requestid
      - Art
      - Artistid
      - Presskit
      - Photoid
  /api/v1/ArtistRequest:
    post:
      summary: Post Artistrequest
      description: Post artistrequest.
      operationId: postApiV1Artistrequest
      x-api-path-slug: apiv1artistrequest-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Artistrequest
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---