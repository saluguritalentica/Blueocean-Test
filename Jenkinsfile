pipeline {
  agent any
  stages {
    stage('Buid') {
      steps {
        sh '''chown test test /jenkins/
chmod 777 ./jenkins/test.sh
./jenkins/test.sh'''
      }
    }
  }
}