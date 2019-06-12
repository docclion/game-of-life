#!groovy

pipeline {
  agent {
      label 'build'
      }
  stages {
    stage('Build') {
      steps {
        sh '/home/ssoza/workspace/pipetest/ mvn package'
      }
    }
  }
}
