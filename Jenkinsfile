pipeline {
  agent any
  stages {
    stage('Buid') {
      steps {
        sh '''chmod 755 ./jenkins/test.sh
./jenkins/test.sh'''
        mail(subject: 'build', body: 'test', from: 'sampathaluguri01@gmail.com', to: 'sampathaluguri01@gmail.com')
      }
    }
  }
}