swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
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