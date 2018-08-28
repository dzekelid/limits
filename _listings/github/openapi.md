swagger: "2.0"
x-collection-name: GitHub
x-complete: 1
info:
  title: GitHub
  version: 1.0.0
host: api.github.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rate_limit:
    get:
      summary: Get Rate Limit
      description: |-
        Get your current rate limit status
        Note: Accessing this endpoint does not count against your rate limit.
      operationId: get-your-current-rate-limit-statusnote-accessing-this-endpoint-does-not-count-against-your-rate-limi
      x-api-path-slug: rate-limit-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      responses:
        200:
          description: OK
      tags:
      - Rate
      - Limit