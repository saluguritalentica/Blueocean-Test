pipeline {
  agent any
  stages {
    stage('Buid') {
      steps {
        sh '''chmod 755 ./jenkins/test.sh

bash -x ./jenkins/test.sh'''
      }
    }
  }
}