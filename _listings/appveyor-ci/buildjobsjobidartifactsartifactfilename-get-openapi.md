---
swagger: "2.0"
x-collection-name: AppVeyor CI
x-complete: 0
info:
  title: App Veyor Get Buildjobs Jobid Artifacts Artifactfilename
  description: Get buildjobs jobid artifacts artifactfilename.
  termsOfService: https://www.appveyor.com/terms-of-service/
  contact:
    name: AppVeyor Team
    url: https://www.appveyor.com/about/
    email: team@appveyor.com
  version: 0.20170106.0
host: ci.appveyor.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account/encrypt:
    post:
      summary: Post Account Encrypt
      description: Post account encrypt.
      operationId: postAccountEncrypt
      x-api-path-slug: accountencrypt-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Account
      - Encrypt
  /buildjobs/{jobId}/artifacts:
    get:
      summary: Get Buildjobs Jobid Artifacts
      description: Get buildjobs jobid artifacts.
      operationId: getBuildjobsJobArtifacts
      x-api-path-slug: buildjobsjobidartifacts-get
      responses:
        200:
          description: OK
      tags:
      - Builds
      - Jobs
      - ""
      - Artifacts
    parameters:
      summary: Parameters Buildjobs Jobid Artifacts
      description: Parameters buildjobs jobid artifacts.
      operationId: parametersBuildjobsJobArtifacts
      x-api-path-slug: buildjobsjobidartifacts-parameters
      responses:
        200:
          description: OK
      tags:
      - Builds
      - Jobs
      - ""
      - Artifacts
  /buildjobs/{jobId}/artifacts/{artifactFileName}:
    get:
      summary: Get Buildjobs Jobid Artifacts Artifactfilename
      description: Get buildjobs jobid artifacts artifactfilename.
      operationId: getBuildjobsJobArtifactsArtifactfilename
      x-api-path-slug: buildjobsjobidartifactsartifactfilename-get
      responses:
        200:
          description: OK
      tags:
      - Builds
      - Jobs
      - ""
      - Artifacts
      - Files
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