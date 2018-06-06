pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''chmod 777 ./jenkins/test.sh
./jenkins/test.sh'''
        sh '''chmod 777 ./jenkins/stopaerospikeservice.sh

'''
      }
    }
  }
}