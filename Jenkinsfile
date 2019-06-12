pipeline {
  agent {
      label 'master'
      }
  stages {
    stage('Build') {
      steps {
        build(quietPeriod: -2, job: '1')
        sh '/home/ssoza/github/game-of-life/ mvn package'
      }
    }
  }
}
