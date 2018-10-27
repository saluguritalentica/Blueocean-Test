pipeline {
  agent any
  stages {
    stage('Buid') {
      steps {
        sh '''chmod 755 ./jenkins/test.sh

sh ./jenkins/test.sh'''
      }
    }
  }
}