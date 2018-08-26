---
swagger: "2.0"
x-collection-name: AWS Storage Gateway Service
x-complete: 0
info:
  title: AWS Storage Gateway Service API Update Bandwidth Rate Limit
  version: 1.0.0
  description: Updates the bandwidth rate limits of a gateway.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteBandwidthRateLimit:
    get:
      summary: Delete Bandwidth Rate Limit
      description: Deletes the bandwidth rate limits of a gateway.
      operationId: deleteBandwidthRateLimit
      x-api-path-slug: actiondeletebandwidthratelimit-get
      parameters:
      - in: query
        name: BandwidthType
        description: One of the BandwidthType values that indicates the gateway         bandwidth
          rate limit to delete
        type: string
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Bandwidth Rate Limit
  /?Action=DescribeBandwidthRateLimit:
    get:
      summary: Describe Bandwidth Rate Limit
      description: Returns the bandwidth rate limits of a gateway.
      operationId: describeBandwidthRateLimit
      x-api-path-slug: actiondescribebandwidthratelimit-get
      parameters:
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Bandwidth Rate Limit
  /?Action=UpdateBandwidthRateLimit:
    get:
      summary: Update Bandwidth Rate Limit
      description: Updates the bandwidth rate limits of a gateway.
      operationId: updateBandwidthRateLimit
      x-api-path-slug: actionupdatebandwidthratelimit-get
      parameters:
      - in: query
        name: AverageDownloadRateLimitInBitsPerSec
        description: The average download bandwidth rate limit in bits per second
        type: string
      - in: query
        name: AverageUploadRateLimitInBitsPerSec
        description: The average upload bandwidth rate limit in bits per second
        type: string
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Bandwidth Rate Limit
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