---
swagger: "2.0"
x-collection-name: Google Cloud Prediction
x-complete: 0
info:
  title: Google Cloud Prediction API Analyze
  description: Get analysis of the model and the data the model was trained on.
  contact:
    name: Google
    url: https://google.com
  version: v1.6
host: www.googleapis.com
basePath: /prediction/v1.6/projects
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{project}/trainedmodels/{id}/analyze:
    get:
      summary: Analyze
      description: Get analysis of the model and the data the model was trained on.
      operationId: prediction.trainedmodels.analyze
      x-api-path-slug: projecttrainedmodelsidanalyze-get
      parameters:
      - in: path
        name: id
        description: The unique name for the predictive model
      - in: path
        name: project
        description: The project associated with the model
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Model
      - Analysis
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