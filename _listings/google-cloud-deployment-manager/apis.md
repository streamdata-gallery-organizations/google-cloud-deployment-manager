---
name: Google Cloud Deployment Manager
x-slug: google-cloud-deployment-manager
description: Google Cloud Deployment Manager allows you to specify all the resources
  needed for your application in a declarative format using yaml. You can also use
  Python or Jinja2 templates to parameterize the configuration and allow reuse of
  common deployment paradigms such as a load balanced, auto-scaled instance group.
  Treat your configuration as code and perform repeatable deployments.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Cloud Deployment Manager
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Deployment Manager Get Deployments
  x-api-slug: google-cloud-deployment-manager
  description: Lists all deployments for a given project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments
  tags: Deployment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeployments-get-openapi.md
- name: Google Cloud Deployment Manager Create Deployment
  x-api-slug: google-cloud-deployment-manager
  description: Creates a deployment and all of the resources described by the deployment
    manifest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeployments-post-openapi.md
- name: Google Cloud Deployment Manager Delete Deployment
  x-api-slug: google-cloud-deployment-manager
  description: Deletes a deployment and all of the resources in the deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeployment-delete-openapi.md
- name: Google Cloud Deployment Manager Get Deployment
  x-api-slug: google-cloud-deployment-manager
  description: Gets information about a specific deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeployment-get-openapi.md
- name: Google Cloud Deployment Manager update Deployment
  x-api-slug: google-cloud-deployment-manager
  description: Updates a deployment and all of the resources described by the deployment
    manifest. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeployment-patch-openapi.md
- name: Google Cloud Deployment Manager update Deployment
  x-api-slug: google-cloud-deployment-manager
  description: Updates a deployment and all of the resources described by the deployment
    manifest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeployment-put-openapi.md
- name: Google Cloud Deployment Manager Cancel Preview
  x-api-slug: google-cloud-deployment-manager
  description: Cancels and removes the preview currently associated with the deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}/cancelPreview
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeploymentcancelpreview-post-openapi.md
- name: Google Cloud Deployment Manager List Manifests
  x-api-slug: google-cloud-deployment-manager
  description: Lists all manifests for a given deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}/manifests
  tags: Manifest
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeploymentmanifests-get-openapi.md
- name: Google Cloud Deployment Manager Get Manifest
  x-api-slug: google-cloud-deployment-manager
  description: Gets information about a specific manifest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}/manifests/{manifest}
  tags: Manifest
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeploymentmanifestsmanifest-get-openapi.md
- name: Google Cloud Deployment Manager List Resources
  x-api-slug: google-cloud-deployment-manager
  description: Lists all resources in a given deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}/resources
  tags: Resource
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeploymentresources-get-openapi.md
- name: Google Cloud Deployment Manager Get Resource
  x-api-slug: google-cloud-deployment-manager
  description: Gets information about a single resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}/resources/{resource}
  tags: Resource
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeploymentresourcesresource-get-openapi.md
- name: Google Cloud Deployment Manager Stop Deployment
  x-api-slug: google-cloud-deployment-manager
  description: Stops an ongoing operation. This does not roll back any work that has
    already been completed, but prevents any new work from being started.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}/stop
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeploymentstop-post-openapi.md
- name: Google Cloud Deployment Manager Get IAM Policy
  x-api-slug: google-cloud-deployment-manager
  description: Gets the access control policy for a resource. May be empty if no such
    policy or resource exists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{resource}/getIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsresourcegetiampolicy-get-openapi.md
- name: Google Cloud Deployment Manager Set IAM Policy
  x-api-slug: google-cloud-deployment-manager
  description: Sets the access control policy on the specified resource. Replaces
    any existing policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{resource}/setIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsresourcesetiampolicy-post-openapi.md
- name: Google Cloud Deployment Manager Test IAM Permission
  x-api-slug: google-cloud-deployment-manager
  description: Returns permissions that a caller has on the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{resource}/testIamPermissions
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsresourcetestiampermissions-post-openapi.md
- name: Google Cloud Deployment Manager Get Operations
  x-api-slug: google-cloud-deployment-manager
  description: Lists all operations for a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/operations
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaloperations-get-openapi.md
- name: Google Cloud Deployment Manager Get Operation
  x-api-slug: google-cloud-deployment-manager
  description: Gets information about a specific operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/operations/{operation}
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaloperationsoperation-get-openapi.md
- name: Google Cloud Deployment Manager Get Types
  x-api-slug: google-cloud-deployment-manager
  description: Lists all resource types for Deployment Manager.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/types
  tags: TYpe
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/projectglobaltypes-get-openapi.md
- name: Google Cloud Deployment Manager Delete Operation
  x-api-slug: google-cloud-deployment-manager
  description: |-
    Deletes a long-running operation. This method indicates that the client is
    no longer interested in the operation result. It does not cancel the
    operation. If the server doesn't support this method, it returns
    `google.rpc.Code.UNIMPLEMENTED`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///v1/{name}
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/v1name-delete-openapi.md
- name: Google Cloud Deployment Manager Get Operations
  x-api-slug: google-cloud-deployment-manager
  description: |-
    Lists operations that match the specified filter in the request. If the
    server doesn't support this method, it returns `UNIMPLEMENTED`.

    NOTE: the `name` binding below allows API services to override the binding
    to use different resource name schemes, such as `users/*/operations`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///v1/{name}
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/v1name-get-openapi.md
- name: Google Cloud Deployment Manager Cancel Operation
  x-api-slug: google-cloud-deployment-manager
  description: |-
    Starts asynchronous cancellation on a long-running operation.  The server
    makes a best effort to cancel the operation, but success is not
    guaranteed.  If the server doesn't support this method, it returns
    `google.rpc.Code.UNIMPLEMENTED`.  Clients can use
    Operations.GetOperation or
    other methods to check whether the cancellation succeeded or whether the
    operation completed despite cancellation. On successful cancellation,
    the operation is not deleted; instead, it becomes an operation with
    an Operation.error value with a google.rpc.Status.code of 1,
    corresponding to `Code.CANCELLED`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///v1/{name}:cancel
  tags: Operation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/v1namecancel-post-openapi.md
- name: Google Cloud Deployment Manager
  x-api-slug: google-cloud-deployment-manager
  description: Google Cloud Deployment Manager allows you to specify all the resources
    needed for your application in a declarative format using yaml. You can also use
    Python or Jinja2 templates to parameterize the configuration and allow reuse of
    common deployment paradigms such as a load balanced, auto-scaled instance group.
    Treat your configuration as code and perform repeatable deployments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https:///
  tags: Google Cloud Deployment Manager
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-deployment-manager/master/_listings/google-cloud-deployment-manager/openapi.md
x-common:
- type: x-authentication
  url: https://cloud.google.com/deployment-manager/docs/reference/latest/authorization
- type: x-change-log
  url: https://cloud.google.com/deployment-manager/docs/release-notes
- type: x-code
  url: https://cloud.google.com/deployment-manager/docs/reference/latest/libraries
- type: x-concepts
  url: https://cloud.google.com/deployment-manager/docs/concepts
- type: x-documentation
  url: https://cloud.google.com/deployment-manager/docs/
- type: x-getting-started
  url: https://cloud.google.com/deployment-manager/docs/quickstart
- type: x-guides
  url: https://cloud.google.com/deployment-manager/docs/how-to
- type: x-pricing
  url: https://cloud.google.com/deployment-manager/pricing-and-quotas
- type: x-tutorials
  url: https://cloud.google.com/deployment-manager/docs/tutorials
- type: x-website
  url: https://cloud.google.com/deployment-manager/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---