pipeline {
  agent any
  stages {
    stage('Buid') {
      steps {
        sh '''chmod 755 ./jenkins/test.sh
./jenkins/test.sh'''
      }
    }
    stage('report') {
      steps {
        junit(testResults: './jenkins/result.xml', allowEmptyResults: true)
      }
    }
  }
}