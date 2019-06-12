pipeline {
  agent {
      label 'build'
      }
  stages {
    stage('Build') {
      steps {
        build(quietPeriod: -2, job: '1')
        sh '/home/ssoza/workspace/pipetest/ mvn package'
      }
    }
  }
}
