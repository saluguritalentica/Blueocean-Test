pipeline {
  agent any
  stages {
    stage('Buid') {
      steps {
        sh '''chmod 755 ./jenkins/test.sh

/jenkins/test.sh'''
      }
    }
  }
}