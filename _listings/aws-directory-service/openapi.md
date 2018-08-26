---
swagger: "2.0"
x-collection-name: AWS Directory Service
x-complete: 1
info:
  title: AWS Directory Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetDirectoryLimits:
    get:
      summary: Get Directory Limits
      description: Obtains directory limit information for the current region.
      operationId: getDirectoryLimits
      x-api-path-slug: actiongetdirectorylimits-get
      parameters:
      - in: query
        name: DirectoryLimits
        description: A DirectoryLimits object that contains the directory limits for
          the current         region
        type: string
      responses:
        200:
          description: OK
      tags:
      - Directories
  /?Action=GetSnapshotLimits:
    get:
      summary: Get Snapshot Limits
      description: Obtains the manual snapshot limits for a directory.
      operationId: getSnapshotLimits
      x-api-path-slug: actiongetsnapshotlimits-get
      parameters:
      - in: query
        name: DirectoryId
        description: Contains the identifier of the directory to obtain the limits
          for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshots
---