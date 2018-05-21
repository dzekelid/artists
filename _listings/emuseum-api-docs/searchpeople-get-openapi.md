---
swagger: "2.0"
x-collection-name: eMuseum API docs
x-complete: 0
info:
  title: eMuseum API Artists
  description: Search for an artist
  version: 1.0.0
host: gsafinearts.pbs.gsa.gov
basePath: /emuseum/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /search/people:
    get:
      summary: Artists
      description: Search for an artist
      operationId: searchArtists
      x-api-path-slug: searchpeople-get
      responses:
        200:
          description: OK
      tags:
      - Artists
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