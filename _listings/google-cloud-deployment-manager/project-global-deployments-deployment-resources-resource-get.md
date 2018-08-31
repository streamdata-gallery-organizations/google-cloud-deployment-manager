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
  /{project}/global/deployments/{deployment}/resources/{resource}:
    get:
      summary: Get Resource
      description: Gets information about a single resource
      operationId: deploymentmanager.resources.get
      parameters:
      - in: path
        name: deployment
        description: The name of the deployment for this request
      - in: path
        name: project
        description: The project ID for this request
      - in: path
        name: resource
        description: The name of the resource for this request
      responses:
        200:
          description: OK
      tags:
      - resource
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