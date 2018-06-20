---
swagger: "2.0"
x-collection-name: AppVeyor CI
x-complete: 0
info:
  title: App Veyor Get Projects Accountname Projectslug
  description: Get projects accountname projectslug.
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
    parameters:
      summary: Parameters Buildjobs Jobid Artifacts Artifactfilename
      description: Parameters buildjobs jobid artifacts artifactfilename.
      operationId: parametersBuildjobsJobArtifactsArtifactfilename
      x-api-path-slug: buildjobsjobidartifactsartifactfilename-parameters
      responses:
        200:
          description: OK
      tags:
      - Builds
      - Jobs
      - ""
      - Artifacts
      - Files
  /buildjobs/{jobId}/log:
    get:
      summary: Get Buildjobs Jobid Log
      description: Get buildjobs jobid log.
      operationId: getBuildjobsJobLog
      x-api-path-slug: buildjobsjobidlog-get
      responses:
        200:
          description: OK
      tags:
      - Builds
      - Jobs
      - ""
      - Log
    parameters:
      summary: Parameters Buildjobs Jobid Log
      description: Parameters buildjobs jobid log.
      operationId: parametersBuildjobsJobLog
      x-api-path-slug: buildjobsjobidlog-parameters
      responses:
        200:
          description: OK
      tags:
      - Builds
      - Jobs
      - ""
      - Log
  /builds:
    post:
      summary: Post Builds
      description: Post builds.
      operationId: postBuilds
      x-api-path-slug: builds-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Builds
  /builds/{accountName}/{projectSlug}/{buildVersion}:
    delete:
      summary: Delete Builds Accountname Projectslug Buildversion
      description: Delete builds accountname projectslug buildversion.
      operationId: deleteBuildsAccountnameProjectslugBuildversion
      x-api-path-slug: buildsaccountnameprojectslugbuildversion-delete
      responses:
        200:
          description: OK
      tags:
      - Builds
      - AccountName
      - ProjectSlug
      - BuildVersion
    parameters:
      summary: Parameters Builds Accountname Projectslug Buildversion
      description: Parameters builds accountname projectslug buildversion.
      operationId: parametersBuildsAccountnameProjectslugBuildversion
      x-api-path-slug: buildsaccountnameprojectslugbuildversion-parameters
      responses:
        200:
          description: OK
      tags:
      - Builds
      - AccountName
      - ProjectSlug
      - BuildVersion
  /collaborators:
    get:
      summary: Get Collaborators
      description: Get collaborators.
      operationId: getCollaborators
      x-api-path-slug: collaborators-get
      responses:
        200:
          description: OK
      tags:
      - Collaborators
    post:
      summary: Post Collaborators
      description: Post collaborators.
      operationId: postCollaborators
      x-api-path-slug: collaborators-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Collaborators
    put:
      summary: Put Collaborators
      description: Put collaborators.
      operationId: putCollaborators
      x-api-path-slug: collaborators-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Collaborators
  /collaborators/{userId}:
    delete:
      summary: Delete Collaborators Userid
      description: Delete collaborators userid.
      operationId: deleteCollaboratorsUser
      x-api-path-slug: collaboratorsuserid-delete
      responses:
        200:
          description: OK
      tags:
      - Collaborators
      - Users
    get:
      summary: Get Collaborators Userid
      description: Get collaborators userid.
      operationId: getCollaboratorsUser
      x-api-path-slug: collaboratorsuserid-get
      responses:
        200:
          description: OK
      tags:
      - Collaborators
      - Users
    parameters:
      summary: Parameters Collaborators Userid
      description: Parameters collaborators userid.
      operationId: parametersCollaboratorsUser
      x-api-path-slug: collaboratorsuserid-parameters
      responses:
        200:
          description: OK
      tags:
      - Collaborators
      - Users
  /deployments:
    post:
      summary: Post Deployments
      description: Post deployments.
      operationId: postDeployments
      x-api-path-slug: deployments-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Deployments
  /deployments/stop:
    delete:
      summary: Delete Deployments Stop
      description: Delete deployments stop.
      operationId: deleteDeploymentsStop
      x-api-path-slug: deploymentsstop-delete
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Deployments
      - Stop
  /deployments/{deploymentId}:
    get:
      summary: Get Deployments Deploymentid
      description: Get deployments deploymentid.
      operationId: getDeploymentsDeployment
      x-api-path-slug: deploymentsdeploymentid-get
      responses:
        200:
          description: OK
      tags:
      - Deployments
      - DeploymentId
    parameters:
      summary: Parameters Deployments Deploymentid
      description: Parameters deployments deploymentid.
      operationId: parametersDeploymentsDeployment
      x-api-path-slug: deploymentsdeploymentid-parameters
      responses:
        200:
          description: OK
      tags:
      - Deployments
      - DeploymentId
  /environments:
    get:
      summary: Get Environments
      description: Get environments.
      operationId: getEnvironments
      x-api-path-slug: environments-get
      responses:
        200:
          description: OK
      tags:
      - Environments
    post:
      summary: Post Environments
      description: Post environments.
      operationId: postEnvironments
      x-api-path-slug: environments-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Environments
    put:
      summary: Put Environments
      description: Put environments.
      operationId: putEnvironments
      x-api-path-slug: environments-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Environments
  /environments/{deploymentEnvironmentId}:
    delete:
      summary: Delete Environments Deploymentenvironmentid
      description: Delete environments deploymentenvironmentid.
      operationId: deleteEnvironmentsDeploymentenvironment
      x-api-path-slug: environmentsdeploymentenvironmentid-delete
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
    parameters:
      summary: Parameters Environments Deploymentenvironmentid
      description: Parameters environments deploymentenvironmentid.
      operationId: parametersEnvironmentsDeploymentenvironment
      x-api-path-slug: environmentsdeploymentenvironmentid-parameters
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
  /environments/{deploymentEnvironmentId}/deployments:
    get:
      summary: Get Environments Deploymentenvironmentid Deployments
      description: Get environments deploymentenvironmentid deployments.
      operationId: getEnvironmentsDeploymentenvironmentDeployments
      x-api-path-slug: environmentsdeploymentenvironmentiddeployments-get
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
      - Deployments
    parameters:
      summary: Parameters Environments Deploymentenvironmentid Deployments
      description: Parameters environments deploymentenvironmentid deployments.
      operationId: parametersEnvironmentsDeploymentenvironmentDeployments
      x-api-path-slug: environmentsdeploymentenvironmentiddeployments-parameters
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
      - Deployments
  /environments/{deploymentEnvironmentId}/settings:
    get:
      summary: Get Environments Deploymentenvironmentid Settings
      description: Get environments deploymentenvironmentid settings.
      operationId: getEnvironmentsDeploymentenvironmentSettings
      x-api-path-slug: environmentsdeploymentenvironmentidsettings-get
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
      - Settings
    parameters:
      summary: Parameters Environments Deploymentenvironmentid Settings
      description: Parameters environments deploymentenvironmentid settings.
      operationId: parametersEnvironmentsDeploymentenvironmentSettings
      x-api-path-slug: environmentsdeploymentenvironmentidsettings-parameters
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
      - Settings
  /projects:
    get:
      summary: Get Projects
      description: Get projects.
      operationId: getProjects
      x-api-path-slug: projects-get
      responses:
        200:
          description: OK
      tags:
      - Projects
    post:
      summary: Post Projects
      description: Post projects.
      operationId: postProjects
      x-api-path-slug: projects-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Projects
    put:
      summary: Put Projects
      description: Put projects.
      operationId: putProjects
      x-api-path-slug: projects-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Projects
  /projects/status/{badgeRepoProvider}/{repoAccountName}/{repoSlug}:
    get:
      summary: Get Projects Status Badgerepoprover Repoaccountname Reposlug
      description: Get projects status badgerepoprover repoaccountname reposlug.
      operationId: getProjectsStatusBadgerepoproverRepoaccountnameReposlug
      x-api-path-slug: projectsstatusbadgerepoproviderrepoaccountnamereposlug-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Status
      - BadgeRepoProvider
      - RepoAccountName
      - RepoSlug
    parameters:
      summary: Parameters Projects Status Badgerepoprover Repoaccountname Reposlug
      description: Parameters projects status badgerepoprover repoaccountname reposlug.
      operationId: parametersProjectsStatusBadgerepoproverRepoaccountnameReposlug
      x-api-path-slug: projectsstatusbadgerepoproviderrepoaccountnamereposlug-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Status
      - BadgeRepoProvider
      - RepoAccountName
      - RepoSlug
  /projects/status/{statusBadgeId}:
    get:
      summary: Get Projects Status Statusbadgeid
      description: Get projects status statusbadgeid.
      operationId: getProjectsStatusStatusbadge
      x-api-path-slug: projectsstatusstatusbadgeid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Status
      - StatusBadgeId
    parameters:
      summary: Parameters Projects Status Statusbadgeid
      description: Parameters projects status statusbadgeid.
      operationId: parametersProjectsStatusStatusbadge
      x-api-path-slug: projectsstatusstatusbadgeid-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Status
      - StatusBadgeId
  /projects/status/{statusBadgeId}/branch/{buildBranch}:
    get:
      summary: Get Projects Status Statusbadgeid Branch Buildbranch
      description: Get projects status statusbadgeid branch buildbranch.
      operationId: getProjectsStatusStatusbadgeBranchBuildbranch
      x-api-path-slug: projectsstatusstatusbadgeidbranchbuildbranch-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Status
      - StatusBadgeId
      - Branch
      - BuildBranch
    parameters:
      summary: Parameters Projects Status Statusbadgeid Branch Buildbranch
      description: Parameters projects status statusbadgeid branch buildbranch.
      operationId: parametersProjectsStatusStatusbadgeBranchBuildbranch
      x-api-path-slug: projectsstatusstatusbadgeidbranchbuildbranch-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Status
      - StatusBadgeId
      - Branch
      - BuildBranch
  /projects/{accountName}/{projectSlug}:
    delete:
      summary: Delete Projects Accountname Projectslug
      description: Delete projects accountname projectslug.
      operationId: deleteProjectsAccountnameProjectslug
      x-api-path-slug: projectsaccountnameprojectslug-delete
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
    get:
      summary: Get Projects Accountname Projectslug
      description: Get projects accountname projectslug.
      operationId: getProjectsAccountnameProjectslug
      x-api-path-slug: projectsaccountnameprojectslug-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
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