---
swagger: "2.0"
x-collection-name: Kubernetes
x-complete: 0
info:
  title: Kubernetes Post Namespaces Limitranges
  version: 1.0.0
  description: Create a limitrange.
host: /api/v1beta3
basePath: 127.0.0.1:6443
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1beta3/limitranges:
    get:
      summary: Get Limitranges
      description: List objects of kind limitrange.
      operationId: listLimitRange
      x-api-path-slug: apiv1beta3limitranges-get
      responses:
        200:
          description: OK
      tags:
      - Limitranges
  /api/v1beta3/namespaces/{namespaces}/limitranges:
    get:
      summary: Get Namespaces Limitranges
      description: List objects of kind limitrange.
      operationId: listLimitRange
      x-api-path-slug: apiv1beta3namespacesnamespaceslimitranges-get
      parameters:
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Namespaces
      - Limitranges
    post:
      summary: Post Namespaces Limitranges
      description: Create a limitrange.
      operationId: createLimitRange
      x-api-path-slug: apiv1beta3namespacesnamespaceslimitranges-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Namespaces
      - Limitranges
  /api/v1beta3/namespaces/{namespaces}/limitranges/{name}:
    delete:
      summary: Delete Namespaces Limitranges Name
      description: Delete a limitrange.
      operationId: deleteLimitRange
      x-api-path-slug: apiv1beta3namespacesnamespaceslimitrangesname-delete
      parameters:
      - in: path
        name: name
        description: name of the LimitRange
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Namespaces
      - Limitranges
      - Name
    get:
      summary: Get Namespaces Limitranges Name
      description: Read the specified limitrange.
      operationId: readLimitRange
      x-api-path-slug: apiv1beta3namespacesnamespaceslimitrangesname-get
      parameters:
      - in: path
        name: name
        description: name of the LimitRange
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Namespaces
      - Limitranges
      - Name
    put:
      summary: Put Namespaces Limitranges Name
      description: Update the specified limitrange.
      operationId: updateLimitRange
      x-api-path-slug: apiv1beta3namespacesnamespaceslimitrangesname-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: name of the LimitRange
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Namespaces
      - Limitranges
      - Name
  /api/v1beta3/watch/limitranges:
    get:
      summary: Get Watch Limitranges
      description: Watch a list of limitrange.
      operationId: watchLimitRangelist
      x-api-path-slug: apiv1beta3watchlimitranges-get
      responses:
        200:
          description: OK
      tags:
      - Watch
      - Limitranges
  /api/v1beta3/watch/namespaces/{namespaces}/limitranges:
    get:
      summary: Get Watch Namespaces Limitranges
      description: Watch a list of limitrange.
      operationId: watchLimitRangelist
      x-api-path-slug: apiv1beta3watchnamespacesnamespaceslimitranges-get
      parameters:
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Watch
      - Namespaces
      - Limitranges
  /api/v1beta3/watch/namespaces/{namespaces}/limitranges/{name}:
    get:
      summary: Get Watch Namespaces Limitranges Name
      description: Watch a particular limitrange.
      operationId: watchLimitRange
      x-api-path-slug: apiv1beta3watchnamespacesnamespaceslimitrangesname-get
      parameters:
      - in: path
        name: name
        description: name of the LimitRange
      - in: path
        name: namespaces
        description: object name and auth scope, such as for teams and projects
      responses:
        200:
          description: OK
      tags:
      - Watch
      - Namespaces
      - Limitranges
      - Name
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