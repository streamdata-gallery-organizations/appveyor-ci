---
swagger: "2.0"
x-collection-name: AppVeyor CI
x-complete: 0
info:
  title: App Veyor Put Roles
  description: Put roles.
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
    parameters:
      summary: Parameters Projects Accountname Projectslug
      description: Parameters projects accountname projectslug.
      operationId: parametersProjectsAccountnameProjectslug
      x-api-path-slug: projectsaccountnameprojectslug-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
  /projects/{accountName}/{projectSlug}/artifacts/{artifactFileName}:
    get:
      summary: Get Projects Accountname Projectslug Artifacts Artifactfilename
      description: Get projects accountname projectslug artifacts artifactfilename.
      operationId: getProjectsAccountnameProjectslugArtifactsArtifactfilename
      x-api-path-slug: projectsaccountnameprojectslugartifactsartifactfilename-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Artifacts
      - Files
    parameters:
      summary: Parameters Projects Accountname Projectslug Artifacts Artifactfilename
      description: Parameters projects accountname projectslug artifacts artifactfilename.
      operationId: parametersProjectsAccountnameProjectslugArtifactsArtifactfilename
      x-api-path-slug: projectsaccountnameprojectslugartifactsartifactfilename-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Artifacts
      - Files
  /projects/{accountName}/{projectSlug}/branch/{buildBranch}:
    get:
      summary: Get Projects Accountname Projectslug Branch Buildbranch
      description: Get projects accountname projectslug branch buildbranch.
      operationId: getProjectsAccountnameProjectslugBranchBuildbranch
      x-api-path-slug: projectsaccountnameprojectslugbranchbuildbranch-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Branch
      - BuildBranch
    parameters:
      summary: Parameters Projects Accountname Projectslug Branch Buildbranch
      description: Parameters projects accountname projectslug branch buildbranch.
      operationId: parametersProjectsAccountnameProjectslugBranchBuildbranch
      x-api-path-slug: projectsaccountnameprojectslugbranchbuildbranch-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Branch
      - BuildBranch
  /projects/{accountName}/{projectSlug}/build/{buildVersion}:
    get:
      summary: Get Projects Accountname Projectslug Build Buildversion
      description: Get projects accountname projectslug build buildversion.
      operationId: getProjectsAccountnameProjectslugBuildBuildversion
      x-api-path-slug: projectsaccountnameprojectslugbuildbuildversion-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Build
      - BuildVersion
    parameters:
      summary: Parameters Projects Accountname Projectslug Build Buildversion
      description: Parameters projects accountname projectslug build buildversion.
      operationId: parametersProjectsAccountnameProjectslugBuildBuildversion
      x-api-path-slug: projectsaccountnameprojectslugbuildbuildversion-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Build
      - BuildVersion
  /projects/{accountName}/{projectSlug}/buildcache:
    delete:
      summary: Delete Projects Accountname Projectslug Buildcache
      description: Delete projects accountname projectslug buildcache.
      operationId: deleteProjectsAccountnameProjectslugBuildcache
      x-api-path-slug: projectsaccountnameprojectslugbuildcache-delete
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Buildcache
    parameters:
      summary: Parameters Projects Accountname Projectslug Buildcache
      description: Parameters projects accountname projectslug buildcache.
      operationId: parametersProjectsAccountnameProjectslugBuildcache
      x-api-path-slug: projectsaccountnameprojectslugbuildcache-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Buildcache
  /projects/{accountName}/{projectSlug}/deployments:
    get:
      summary: Get Projects Accountname Projectslug Deployments
      description: Get projects accountname projectslug deployments.
      operationId: getProjectsAccountnameProjectslugDeployments
      x-api-path-slug: projectsaccountnameprojectslugdeployments-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Deployments
    parameters:
      summary: Parameters Projects Accountname Projectslug Deployments
      description: Parameters projects accountname projectslug deployments.
      operationId: parametersProjectsAccountnameProjectslugDeployments
      x-api-path-slug: projectsaccountnameprojectslugdeployments-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Deployments
  /projects/{accountName}/{projectSlug}/history:
    get:
      summary: Get Projects Accountname Projectslug History
      description: Get projects accountname projectslug history.
      operationId: getProjectsAccountnameProjectslugHistory
      x-api-path-slug: projectsaccountnameprojectslughistory-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - History
    parameters:
      summary: Parameters Projects Accountname Projectslug History
      description: Parameters projects accountname projectslug history.
      operationId: parametersProjectsAccountnameProjectslugHistory
      x-api-path-slug: projectsaccountnameprojectslughistory-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - History
  /projects/{accountName}/{projectSlug}/settings:
    get:
      summary: Get Projects Accountname Projectslug Settings
      description: Get projects accountname projectslug settings.
      operationId: getProjectsAccountnameProjectslugSettings
      x-api-path-slug: projectsaccountnameprojectslugsettings-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
    parameters:
      summary: Parameters Projects Accountname Projectslug Settings
      description: Parameters projects accountname projectslug settings.
      operationId: parametersProjectsAccountnameProjectslugSettings
      x-api-path-slug: projectsaccountnameprojectslugsettings-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
  /projects/{accountName}/{projectSlug}/settings/build-number:
    parameters:
      summary: Parameters Projects Accountname Projectslug Settings Build Number
      description: Parameters projects accountname projectslug settings build number.
      operationId: parametersProjectsAccountnameProjectslugSettingsBuildNumber
      x-api-path-slug: projectsaccountnameprojectslugsettingsbuildnumber-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Build
      - Number
    put:
      summary: Put Projects Accountname Projectslug Settings Build Number
      description: Put projects accountname projectslug settings build number.
      operationId: putProjectsAccountnameProjectslugSettingsBuildNumber
      x-api-path-slug: projectsaccountnameprojectslugsettingsbuildnumber-put
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
      - AccountName
      - ProjectSlug
      - Settings
      - Build
      - Number
  /projects/{accountName}/{projectSlug}/settings/environment-variables:
    get:
      summary: Get Projects Accountname Projectslug Settings Environment Variables
      description: Get projects accountname projectslug settings environment variables.
      operationId: getProjectsAccountnameProjectslugSettingsEnvironmentVariables
      x-api-path-slug: projectsaccountnameprojectslugsettingsenvironmentvariables-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Environment
      - Variables
    parameters:
      summary: Parameters Projects Accountname Projectslug Settings Environment Variables
      description: Parameters projects accountname projectslug settings environment
        variables.
      operationId: parametersProjectsAccountnameProjectslugSettingsEnvironmentVariables
      x-api-path-slug: projectsaccountnameprojectslugsettingsenvironmentvariables-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Environment
      - Variables
    put:
      summary: Put Projects Accountname Projectslug Settings Environment Variables
      description: Put projects accountname projectslug settings environment variables.
      operationId: putProjectsAccountnameProjectslugSettingsEnvironmentVariables
      x-api-path-slug: projectsaccountnameprojectslugsettingsenvironmentvariables-put
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
      - AccountName
      - ProjectSlug
      - Settings
      - Environment
      - Variables
  /projects/{accountName}/{projectSlug}/settings/yaml:
    get:
      summary: Get Projects Accountname Projectslug Settings Yaml
      description: Get projects accountname projectslug settings yaml.
      operationId: getProjectsAccountnameProjectslugSettingsYaml
      x-api-path-slug: projectsaccountnameprojectslugsettingsyaml-get
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Yaml
    parameters:
      summary: Parameters Projects Accountname Projectslug Settings Yaml
      description: Parameters projects accountname projectslug settings yaml.
      operationId: parametersProjectsAccountnameProjectslugSettingsYaml
      x-api-path-slug: projectsaccountnameprojectslugsettingsyaml-parameters
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Yaml
    put:
      summary: Put Projects Accountname Projectslug Settings Yaml
      description: Put projects accountname projectslug settings yaml.
      operationId: putProjectsAccountnameProjectslugSettingsYaml
      x-api-path-slug: projectsaccountnameprojectslugsettingsyaml-put
      parameters:
      - in: body
        name: body
        description: The body of requests should contain YAML data
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Projects
      - AccountName
      - ProjectSlug
      - Settings
      - Yaml
  /roles:
    get:
      summary: Get Roles
      description: Get roles.
      operationId: getRoles
      x-api-path-slug: roles-get
      responses:
        200:
          description: OK
      tags:
      - Roles
    post:
      summary: Post Roles
      description: Post roles.
      operationId: postRoles
      x-api-path-slug: roles-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Roles
    put:
      summary: Put Roles
      description: Put roles.
      operationId: putRoles
      x-api-path-slug: roles-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Roles
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