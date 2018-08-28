---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Deletes a Letter Template
  version: 1.0.0
  description: Deletes a letter template.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/documentgeneration/deletelettertemplate/{id}/{useageLimit}:
    delete:
      summary: Deletes a Letter Template
      description: Deletes a letter template.
      operationId: DocumentGeneration_DeleteLetterTemplateByidByuseageLimit
      x-api-path-slug: apidocumentgenerationdeletelettertemplateiduseagelimit-delete
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: useageLimit
      responses:
        200:
          description: OK
      tags:
      - S
      - Letter
      - Template
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