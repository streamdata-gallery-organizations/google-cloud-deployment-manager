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
  /{project}/global/deployments:
    post:
      summary: Create Deployment
      description: Creates a deployment and all of the resources described by the
        deployment manifest
      operationId: deploymentmanager.deployments.insert
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: preview
        description: If set to true, creates a deployment and creates "shell" resources
          but does not actually instantiate these resources
      - in: path
        name: project
        description: The project ID for this request
      responses:
        200:
          description: OK
      tags:
      - deployment
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