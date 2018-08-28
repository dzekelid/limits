swagger: "2.0"
x-collection-name: AWS DynamoDB
x-complete: 1
info:
  title: AWS DynamoDB API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeLimits:
    get:
      summary: Describe Limits
      description: Returns the current provisioned-capacity limits for your AWS account
        in a region, both for the region as a whole and for any one DynamoDB table
        that you create there.
      operationId: describeLimits
      x-api-path-slug: actiondescribelimits-get
      parameters:
      - in: query
        name: AccountMaxReadCapacityUnits
        description: The maximum total read capacity units that your account allows
          you to provision across all of your tables in this region
        type: string
      - in: query
        name: AccountMaxWriteCapacityUnits
        description: The maximum total write capacity units that your account allows
          you to provision across all of your tables in this region
        type: string
      - in: query
        name: TableMaxReadCapacityUnits
        description: The maximum read capacity units that your account allows you
          to provision for a new table that you are creating in this region, including
          the read capacity units provisioned for its global secondary indexes (GSIs)
        type: string
      - in: query
        name: TableMaxWriteCapacityUnits
        description: The maximum write capacity units that your account allows you
          to provision for a new table that you are creating in this region, including
          the write capacity units provisioned for its global secondary indexes (GSIs)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Limits