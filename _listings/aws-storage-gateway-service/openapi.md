swagger: "2.0"
x-collection-name: AWS Storage Gateway Service
x-complete: 1
info:
  title: AWS Storage Gateway Service API
  version: 1.0.0
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