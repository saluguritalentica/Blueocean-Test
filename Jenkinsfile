pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''chmod 777 ./jenkins/test.sh
./jenkins/test.sh'''
        sh '''chmod 055 ./jenkins/stopaerospikeservice.sh

'''
      }
    }
  }
}