---
swagger: "2.0"
info:
  title: Google Cloud Deployment Manager
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{project}/global/operations/{operation}:
    get:
      summary: Get Operation
      description: Gets information about a specific operation
      operationId: deploymentmanager.operations.get
      parameters:
      - in: path
        name: operation
        description: The name of the operation for this request
      - in: path
        name: project
        description: The project ID for this request
      responses:
        200:
          description: OK
      tags:
      - operation
definitions: []
x-collection-name: Google Cloud Deployment Manager
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