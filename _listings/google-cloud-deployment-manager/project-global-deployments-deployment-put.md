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
  /{project}/global/deployments/{deployment}:
    put:
      summary: update Deployment
      description: Updates a deployment and all of the resources described by the
        deployment manifest
      operationId: deploymentmanager.deployments.update
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: createPolicy
        description: Sets the policy to use for creating new resources
      - in: query
        name: deletePolicy
        description: Sets the policy to use for deleting resources
      - in: path
        name: deployment
        description: The name of the deployment for this request
      - in: query
        name: preview
        description: If set to true, updates the deployment and creates and updates
          the "shell" resources but does not actually alter or instantiate these resources
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