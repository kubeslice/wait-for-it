@Library('jenkins-library@opensource-release') _
dockerImagePipeline(
  script: this,
  service: 'wait-for-it',
  dockerfile: 'Dockerfile',
  buildContext: '.',
  buildArguments: [PLATFORM:"amd64"]
  
)
