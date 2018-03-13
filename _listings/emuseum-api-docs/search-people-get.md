---
swagger: "2.0"
info:
  title: eMuseum API
  description: Developed in partnership with museums, The Museum System makes capturing,
    managing and accessing collection information quick and easy. eMuseum is a web-based
    software program that integrates seamlessly with TMS and other collection management
    systems to dynamically publish information to your website, Intranet, and kiosks.
    This API delivers search information and images from TMS &amp; eMuseum to GSA.gov.
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
      responses:
        200:
          description: OK
      tags:
      - artists
definitions: []
x-collection-name: eMuseum API docs
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