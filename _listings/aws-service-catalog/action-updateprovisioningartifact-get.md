---
swagger: "2.0"
info:
  title: AWS Service Catalog API Update Provisioning Artifact
  version: 1.0.0
  description: Updates an existing provisioning artifact's information.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=UpdateProvisioningArtifact:
    get:
      summary: ' Update Provisioning Artifact '
      description: Updates an existing provisioning artifact's information
      operationId: updateProvisioningArtifact
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Description
        description: The updated text description of the provisioning artifact
        type: string
      - in: query
        name: Name
        description: The updated name of the provisioning artifact
        type: string
      - in: query
        name: ProductId
        description: The product identifier
        type: string
      - in: query
        name: ProvisioningArtifactId
        description: The identifier of the provisioning artifact for the update request
        type: string
      responses:
        200:
          description: OK
      tags:
      - provisioning artifacts
definitions: []
x-collection-name: AWS Service Catalog
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