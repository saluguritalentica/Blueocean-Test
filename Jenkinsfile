pipeline {
  agent any
  stages {
    stage('Buid') {
      steps {
        sh '''chmod 777 ./jenkins/test.sh
./jenkins/test.sh'''
        mail(subject: 'build', body: 'test', to: 'sampathaluguri01@gmail.com')
      }
    }
  }
}