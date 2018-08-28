---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Get API Offchain Limit List
  version: 1.0.0
  description: Get api offchain limit list.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/History/limit/trades:
    get:
      summary: Get API History Limit Trades
      description: Get api history limit trades.
      operationId: ApiHistoryLimitTradesGet
      x-api-path-slug: apihistorylimittrades-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: orderId
      responses:
        200:
          description: OK
      tags:
      - History
      - Limit
      - Trades
  /api/History/limit/order:
    get:
      summary: Get API History Limit Order
      description: Get api history limit order.
      operationId: ApiHistoryLimitOrderGet
      x-api-path-slug: apihistorylimitorder-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: orderId
      responses:
        200:
          description: OK
      tags:
      - History
      - Limit
      - Order
  /api/History/limit/history:
    get:
      summary: Get API History Limit History
      description: Get api history limit history.
      operationId: ApiHistoryLimitHistoryGet
      x-api-path-slug: apihistorylimithistory-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: orderId
      responses:
        200:
          description: OK
      tags:
      - History
      - Limit
      - History
  /api/offchain/limit/list:
    get:
      summary: Get API Offchain Limit List
      description: Get api offchain limit list.
      operationId: ApiOffchainLimitListGet
      x-api-path-slug: apioffchainlimitlist-get
      parameters:
      - in: query
        name: assetPair
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Offchain
      - Limit
      - List
  /api/offchain/limit/count:
    get:
      summary: Get API Offchain Limit Count
      description: Get api offchain limit count.
      operationId: ApiOffchainLimitCountGet
      x-api-path-slug: apioffchainlimitcount-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Offchain
      - Limit
      - Count
  /api/offchain/limit/trade:
    post:
      summary: Add API Offchain Limit Trade
      description: Add api offchain limit trade.
      operationId: ApiOffchainLimitTradePost
      x-api-path-slug: apioffchainlimittrade-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Offchain
      - Limit
      - Trade
  /api/offchain/limit/cancel:
    post:
      summary: Add API Offchain Limit Cancel
      description: Add api offchain limit cancel.
      operationId: ApiOffchainLimitCancelPost
      x-api-path-slug: apioffchainlimitcancel-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Offchain
      - Limit
      - Cancel
  /api/HotWallet/limitOrder:
    post:
      summary: Add API Hotwallet Limitorder
      description: Add api hotwallet limitorder.
      operationId: LimitOrder
      x-api-path-slug: apihotwalletlimitorder-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: SignatureVerificationToken
        description: signature verification token
      responses:
        200:
          description: OK
      tags:
      - Hotwallet
      - Limitorder
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