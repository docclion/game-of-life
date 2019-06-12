#!groovy

pipeline {
  agent {
      label 'build'
      }
  stages {
    stage('Build') {
      steps {
        sh 'cd /home/ssoza/workspace/pipetest mvn package'
        sh 'mvn package'
      }
    }
  }
}
