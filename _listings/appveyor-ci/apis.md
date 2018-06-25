---
name: AppVeyor CI
x-slug: appveyor-ci
description: We provide continuous integration tools for Windows developers. The service
  is offered for free to open-source projects, we offer subscriptions for private
  projects and AppVeyor Enterprise installations on customer premises.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
x-kinRank: "7"
x-alexaRank: "35479"
tags: AppVeyor CI
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/apis.md
specificationVersion: "0.14"
apis:
- name: App Veyor Post Account Encrypt
  x-api-slug: app-veyor
  description: Post account encrypt.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//account/encrypt
  tags: Account,Encrypt
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/accountencrypt-post-openapi.md
- name: App Veyor Get Buildjobs Jobid Artifacts
  x-api-slug: app-veyor
  description: Get buildjobs jobid artifacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//buildjobs/{jobId}/artifacts
  tags: Builds,Jobs,,Artifacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/buildjobsjobidartifacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/buildjobsjobidartifacts-get-openapi.md
- name: App Veyor Parameters Buildjobs Jobid Artifacts
  x-api-slug: app-veyor
  description: Parameters buildjobs jobid artifacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//buildjobs/{jobId}/artifacts
  tags: Builds,Jobs,,Artifacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/buildjobsjobidartifacts-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/buildjobsjobidartifacts-parameters-openapi.md
- name: App Veyor Get Buildjobs Jobid Artifacts Artifactfilename
  x-api-slug: app-veyor
  description: Get buildjobs jobid artifacts artifactfilename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//buildjobs/{jobId}/artifacts/{artifactFileName}
  tags: Builds,Jobs,,Artifacts,Files
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/buildjobsjobidartifactsartifactfilename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/buildjobsjobidartifactsartifactfilename-get-openapi.md
- name: App Veyor Parameters Buildjobs Jobid Artifacts Artifactfilename
  x-api-slug: app-veyor
  description: Parameters buildjobs jobid artifacts artifactfilename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//buildjobs/{jobId}/artifacts/{artifactFileName}
  tags: Builds,Jobs,,Artifacts,Files
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/buildjobsjobidartifactsartifactfilename-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/buildjobsjobidartifactsartifactfilename-parameters-openapi.md
- name: App Veyor Get Buildjobs Jobid Log
  x-api-slug: app-veyor
  description: Get buildjobs jobid log.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//buildjobs/{jobId}/log
  tags: Builds,Jobs,,Log
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/buildjobsjobidlog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/buildjobsjobidlog-get-openapi.md
- name: App Veyor Parameters Buildjobs Jobid Log
  x-api-slug: app-veyor
  description: Parameters buildjobs jobid log.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//buildjobs/{jobId}/log
  tags: Builds,Jobs,,Log
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/buildjobsjobidlog-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/buildjobsjobidlog-parameters-openapi.md
- name: App Veyor Post Builds
  x-api-slug: app-veyor
  description: Post builds.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//builds
  tags: Builds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/builds-post-openapi.md
- name: App Veyor Delete Builds Accountname Projectslug Buildversion
  x-api-slug: app-veyor
  description: Delete builds accountname projectslug buildversion.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//builds/{accountName}/{projectSlug}/{buildVersion}
  tags: Builds,AccountName,ProjectSlug,BuildVersion
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/buildsaccountnameprojectslugbuildversion-delete-openapi.md
- name: App Veyor Parameters Builds Accountname Projectslug Buildversion
  x-api-slug: app-veyor
  description: Parameters builds accountname projectslug buildversion.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//builds/{accountName}/{projectSlug}/{buildVersion}
  tags: Builds,AccountName,ProjectSlug,BuildVersion
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/buildsaccountnameprojectslugbuildversion-parameters-openapi.md
- name: App Veyor Get Collaborators
  x-api-slug: app-veyor
  description: Get collaborators.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//collaborators
  tags: Collaborators
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/collaborators-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/collaborators-get-openapi.md
- name: App Veyor Post Collaborators
  x-api-slug: app-veyor
  description: Post collaborators.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//collaborators
  tags: Collaborators
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/collaborators-post-openapi.md
- name: App Veyor Put Collaborators
  x-api-slug: app-veyor
  description: Put collaborators.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//collaborators
  tags: Collaborators
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/collaborators-put-openapi.md
- name: App Veyor Delete Collaborators Userid
  x-api-slug: app-veyor
  description: Delete collaborators userid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//collaborators/{userId}
  tags: Collaborators,Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/collaboratorsuserid-delete-openapi.md
- name: App Veyor Get Collaborators Userid
  x-api-slug: app-veyor
  description: Get collaborators userid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//collaborators/{userId}
  tags: Collaborators,Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/collaboratorsuserid-get-openapi.md
- name: App Veyor Parameters Collaborators Userid
  x-api-slug: app-veyor
  description: Parameters collaborators userid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//collaborators/{userId}
  tags: Collaborators,Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/collaboratorsuserid-parameters-openapi.md
- name: App Veyor Post Deployments
  x-api-slug: app-veyor
  description: Post deployments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//deployments
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/deployments-post-openapi.md
- name: App Veyor Delete Deployments Stop
  x-api-slug: app-veyor
  description: Delete deployments stop.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//deployments/stop
  tags: Deployments,Stop
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/deploymentsstop-delete-openapi.md
- name: App Veyor Get Deployments Deploymentid
  x-api-slug: app-veyor
  description: Get deployments deploymentid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//deployments/{deploymentId}
  tags: Deployments,DeploymentId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/deploymentsdeploymentid-get-openapi.md
- name: App Veyor Parameters Deployments Deploymentid
  x-api-slug: app-veyor
  description: Parameters deployments deploymentid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//deployments/{deploymentId}
  tags: Deployments,DeploymentId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/deploymentsdeploymentid-parameters-openapi.md
- name: App Veyor Get Environments
  x-api-slug: app-veyor
  description: Get environments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments
  tags: Environments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/environments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/environments-get-openapi.md
- name: App Veyor Post Environments
  x-api-slug: app-veyor
  description: Post environments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/environments-post-openapi.md
- name: App Veyor Put Environments
  x-api-slug: app-veyor
  description: Put environments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/environments-put-openapi.md
- name: App Veyor Delete Environments Deploymentenvironmentid
  x-api-slug: app-veyor
  description: Delete environments deploymentenvironmentid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments/{deploymentEnvironmentId}
  tags: Environments,DeploymentEnvironmentId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/environmentsdeploymentenvironmentid-delete-openapi.md
- name: App Veyor Parameters Environments Deploymentenvironmentid
  x-api-slug: app-veyor
  description: Parameters environments deploymentenvironmentid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments/{deploymentEnvironmentId}
  tags: Environments,DeploymentEnvironmentId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/environmentsdeploymentenvironmentid-parameters-openapi.md
- name: App Veyor Get Environments Deploymentenvironmentid Deployments
  x-api-slug: app-veyor
  description: Get environments deploymentenvironmentid deployments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments/{deploymentEnvironmentId}/deployments
  tags: Environments,DeploymentEnvironmentId,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/environmentsdeploymentenvironmentiddeployments-get-openapi.md
- name: App Veyor Parameters Environments Deploymentenvironmentid Deployments
  x-api-slug: app-veyor
  description: Parameters environments deploymentenvironmentid deployments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments/{deploymentEnvironmentId}/deployments
  tags: Environments,DeploymentEnvironmentId,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/environmentsdeploymentenvironmentiddeployments-parameters-openapi.md
- name: App Veyor Get Environments Deploymentenvironmentid Settings
  x-api-slug: app-veyor
  description: Get environments deploymentenvironmentid settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments/{deploymentEnvironmentId}/settings
  tags: Environments,DeploymentEnvironmentId,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/environmentsdeploymentenvironmentidsettings-get-openapi.md
- name: App Veyor Parameters Environments Deploymentenvironmentid Settings
  x-api-slug: app-veyor
  description: Parameters environments deploymentenvironmentid settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//environments/{deploymentEnvironmentId}/settings
  tags: Environments,DeploymentEnvironmentId,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/environmentsdeploymentenvironmentidsettings-parameters-openapi.md
- name: App Veyor Get Projects
  x-api-slug: app-veyor
  description: Get projects.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projects-get-openapi.md
- name: App Veyor Post Projects
  x-api-slug: app-veyor
  description: Post projects.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projects-post-openapi.md
- name: App Veyor Put Projects
  x-api-slug: app-veyor
  description: Put projects.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects
  tags: Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projects-put-openapi.md
- name: App Veyor Get Projects Status Badgerepoprover Repoaccountname Reposlug
  x-api-slug: app-veyor
  description: Get projects status badgerepoprover repoaccountname reposlug.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/status/{badgeRepoProvider}/{repoAccountName}/{repoSlug}
  tags: Projects,Status,BadgeRepoProvider,RepoAccountName,RepoSlug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsstatusbadgerepoproviderrepoaccountnamereposlug-get-openapi.md
- name: App Veyor Parameters Projects Status Badgerepoprover Repoaccountname Reposlug
  x-api-slug: app-veyor
  description: Parameters projects status badgerepoprover repoaccountname reposlug.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/status/{badgeRepoProvider}/{repoAccountName}/{repoSlug}
  tags: Projects,Status,BadgeRepoProvider,RepoAccountName,RepoSlug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsstatusbadgerepoproviderrepoaccountnamereposlug-parameters-openapi.md
- name: App Veyor Get Projects Status Statusbadgeid
  x-api-slug: app-veyor
  description: Get projects status statusbadgeid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/status/{statusBadgeId}
  tags: Projects,Status,StatusBadgeId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsstatusstatusbadgeid-get-openapi.md
- name: App Veyor Parameters Projects Status Statusbadgeid
  x-api-slug: app-veyor
  description: Parameters projects status statusbadgeid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/status/{statusBadgeId}
  tags: Projects,Status,StatusBadgeId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsstatusstatusbadgeid-parameters-openapi.md
- name: App Veyor Get Projects Status Statusbadgeid Branch Buildbranch
  x-api-slug: app-veyor
  description: Get projects status statusbadgeid branch buildbranch.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/status/{statusBadgeId}/branch/{buildBranch}
  tags: Projects,Status,StatusBadgeId,Branch,BuildBranch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsstatusstatusbadgeidbranchbuildbranch-get-openapi.md
- name: App Veyor Parameters Projects Status Statusbadgeid Branch Buildbranch
  x-api-slug: app-veyor
  description: Parameters projects status statusbadgeid branch buildbranch.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/status/{statusBadgeId}/branch/{buildBranch}
  tags: Projects,Status,StatusBadgeId,Branch,BuildBranch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsstatusstatusbadgeidbranchbuildbranch-parameters-openapi.md
- name: App Veyor Delete Projects Accountname Projectslug
  x-api-slug: app-veyor
  description: Delete projects accountname projectslug.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}
  tags: Projects,AccountName,ProjectSlug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslug-delete-openapi.md
- name: App Veyor Get Projects Accountname Projectslug
  x-api-slug: app-veyor
  description: Get projects accountname projectslug.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}
  tags: Projects,AccountName,ProjectSlug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslug-get-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}
  tags: Projects,AccountName,ProjectSlug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslug-parameters-openapi.md
- name: App Veyor Get Projects Accountname Projectslug Artifacts Artifactfilename
  x-api-slug: app-veyor
  description: Get projects accountname projectslug artifacts artifactfilename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/artifacts/{artifactFileName}
  tags: Projects,AccountName,ProjectSlug,Artifacts,Files
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugartifactsartifactfilename-get-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Artifacts Artifactfilename
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug artifacts artifactfilename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/artifacts/{artifactFileName}
  tags: Projects,AccountName,ProjectSlug,Artifacts,Files
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugartifactsartifactfilename-parameters-openapi.md
- name: App Veyor Get Projects Accountname Projectslug Branch Buildbranch
  x-api-slug: app-veyor
  description: Get projects accountname projectslug branch buildbranch.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/branch/{buildBranch}
  tags: Projects,AccountName,ProjectSlug,Branch,BuildBranch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugbranchbuildbranch-get-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Branch Buildbranch
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug branch buildbranch.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/branch/{buildBranch}
  tags: Projects,AccountName,ProjectSlug,Branch,BuildBranch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugbranchbuildbranch-parameters-openapi.md
- name: App Veyor Get Projects Accountname Projectslug Build Buildversion
  x-api-slug: app-veyor
  description: Get projects accountname projectslug build buildversion.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/build/{buildVersion}
  tags: Projects,AccountName,ProjectSlug,Build,BuildVersion
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugbuildbuildversion-get-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Build Buildversion
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug build buildversion.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/build/{buildVersion}
  tags: Projects,AccountName,ProjectSlug,Build,BuildVersion
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugbuildbuildversion-parameters-openapi.md
- name: App Veyor Delete Projects Accountname Projectslug Buildcache
  x-api-slug: app-veyor
  description: Delete projects accountname projectslug buildcache.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/buildcache
  tags: Projects,AccountName,ProjectSlug,Buildcache
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugbuildcache-delete-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Buildcache
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug buildcache.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/buildcache
  tags: Projects,AccountName,ProjectSlug,Buildcache
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugbuildcache-parameters-openapi.md
- name: App Veyor Get Projects Accountname Projectslug Deployments
  x-api-slug: app-veyor
  description: Get projects accountname projectslug deployments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/deployments
  tags: Projects,AccountName,ProjectSlug,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugdeployments-get-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Deployments
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug deployments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/deployments
  tags: Projects,AccountName,ProjectSlug,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugdeployments-parameters-openapi.md
- name: App Veyor Get Projects Accountname Projectslug History
  x-api-slug: app-veyor
  description: Get projects accountname projectslug history.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/history
  tags: Projects,AccountName,ProjectSlug,History
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslughistory-get-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug History
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug history.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/history
  tags: Projects,AccountName,ProjectSlug,History
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslughistory-parameters-openapi.md
- name: App Veyor Get Projects Accountname Projectslug Settings
  x-api-slug: app-veyor
  description: Get projects accountname projectslug settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings
  tags: Projects,AccountName,ProjectSlug,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettings-get-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Settings
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug settings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings
  tags: Projects,AccountName,ProjectSlug,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettings-parameters-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Settings Build Number
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug settings build number.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/build-number
  tags: Projects,AccountName,ProjectSlug,Settings,Build,Number
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsbuildnumber-parameters-openapi.md
- name: App Veyor Put Projects Accountname Projectslug Settings Build Number
  x-api-slug: app-veyor
  description: Put projects accountname projectslug settings build number.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/build-number
  tags: Projects,AccountName,ProjectSlug,Settings,Build,Number
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsbuildnumber-put-openapi.md
- name: App Veyor Get Projects Accountname Projectslug Settings Environment Variables
  x-api-slug: app-veyor
  description: Get projects accountname projectslug settings environment variables.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/environment-variables
  tags: Projects,AccountName,ProjectSlug,Settings,Environment,Variables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsenvironmentvariables-get-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Settings Environment
    Variables
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug settings environment variables.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/environment-variables
  tags: Projects,AccountName,ProjectSlug,Settings,Environment,Variables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsenvironmentvariables-parameters-openapi.md
- name: App Veyor Put Projects Accountname Projectslug Settings Environment Variables
  x-api-slug: app-veyor
  description: Put projects accountname projectslug settings environment variables.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/environment-variables
  tags: Projects,AccountName,ProjectSlug,Settings,Environment,Variables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsenvironmentvariables-put-openapi.md
- name: App Veyor Get Projects Accountname Projectslug Settings Yaml
  x-api-slug: app-veyor
  description: Get projects accountname projectslug settings yaml.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/yaml
  tags: Projects,AccountName,ProjectSlug,Settings,Yaml
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsyaml-get-openapi.md
- name: App Veyor Parameters Projects Accountname Projectslug Settings Yaml
  x-api-slug: app-veyor
  description: Parameters projects accountname projectslug settings yaml.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/yaml
  tags: Projects,AccountName,ProjectSlug,Settings,Yaml
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsyaml-parameters-openapi.md
- name: App Veyor Put Projects Accountname Projectslug Settings Yaml
  x-api-slug: app-veyor
  description: Put projects accountname projectslug settings yaml.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/{accountName}/{projectSlug}/settings/yaml
  tags: Projects,AccountName,ProjectSlug,Settings,Yaml
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsaccountnameprojectslugsettingsyaml-put-openapi.md
- name: App Veyor Get Roles
  x-api-slug: app-veyor
  description: Get roles.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//roles
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/roles-get-openapi.md
- name: App Veyor Post Roles
  x-api-slug: app-veyor
  description: Post roles.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//roles
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/roles-post-openapi.md
- name: App Veyor Put Roles
  x-api-slug: app-veyor
  description: Put roles.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//roles
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/roles-put-openapi.md
- name: App Veyor Delete Roles Roleid
  x-api-slug: app-veyor
  description: Delete roles roleid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//roles/{roleId}
  tags: Roles,RoleId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/rolesroleid-delete-openapi.md
- name: App Veyor Get Roles Roleid
  x-api-slug: app-veyor
  description: Get roles roleid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//roles/{roleId}
  tags: Roles,RoleId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/rolesroleid-get-openapi.md
- name: App Veyor Parameters Roles Roleid
  x-api-slug: app-veyor
  description: Parameters roles roleid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//roles/{roleId}
  tags: Roles,RoleId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/rolesroleid-parameters-openapi.md
- name: App Veyor Get Users
  x-api-slug: app-veyor
  description: Get users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//users
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/users-get-openapi.md
- name: App Veyor Post Users
  x-api-slug: app-veyor
  description: Post users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//users
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/users-post-openapi.md
- name: App Veyor Put Users
  x-api-slug: app-veyor
  description: Put users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//users
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/users-put-openapi.md
- name: App Veyor Delete Users Userid
  x-api-slug: app-veyor
  description: Delete users userid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//users/{userId}
  tags: Users,Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/usersuserid-delete-openapi.md
- name: App Veyor Get Users Userid
  x-api-slug: app-veyor
  description: Get users userid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//users/{userId}
  tags: Users,Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/usersuserid-get-openapi.md
- name: App Veyor Parameters Users Userid
  x-api-slug: app-veyor
  description: Parameters users userid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//users/{userId}
  tags: Users,Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/usersuserid-parameters-openapi.md
- name: App Veyor Get Projects Status Webhookid
  x-api-slug: app-veyor
  description: Get projects status webhookid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/status/{webhookId}
  tags: Projects,Status,WebhookId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsstatuswebhookid-get-openapi.md
- name: App Veyor Parameters Projects Status Webhookid
  x-api-slug: app-veyor
  description: Parameters projects status webhookid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/status/{webhookId}
  tags: Projects,Status,WebhookId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsstatuswebhookid-parameters-openapi.md
- name: App Veyor Get Projects Status Webhookid Branch Buildbranch
  x-api-slug: app-veyor
  description: Get projects status webhookid branch buildbranch.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/status/{webhookId}/branch/{buildBranch}
  tags: Projects,Status,WebhookId,Branch,BuildBranch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsstatuswebhookidbranchbuildbranch-get-openapi.md
- name: App Veyor Parameters Projects Status Webhookid Branch Buildbranch
  x-api-slug: app-veyor
  description: Parameters projects status webhookid branch buildbranch.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api//projects/status/{webhookId}/branch/{buildBranch}
  tags: Projects,Status,WebhookId,Branch,BuildBranch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/projectsstatuswebhookidbranchbuildbranch-parameters-openapi.md
- name: App Veyor
  x-api-slug: app-veyor
  description: We provide continuous integration tools for Windows developers. The
    service is offered for free to open-source projects, we offer subscriptions for
    private projects and AppVeyor Enterprise installations on customer premises.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28368-app-veyor.jpg
  humanURL: http://appveyor.com
  baseURL: https://ci.appveyor.com//api
  tags: AppVeyor CI
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/appveyor-ci/master/_listings/appveyor-ci/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/appveyor-systems-inc
- type: x-documentation
  url: https://www.appveyor.com/docs/
- type: x-email
  url: jobs@appveyor.com
- type: x-email
  url: team@appveyor.com
- type: x-email
  url: privacy@appveyor.com
- type: x-twitter
  url: https://twitter.com/appveyor
- type: x-website
  url: http://appveyor.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---