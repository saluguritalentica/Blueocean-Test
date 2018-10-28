pipeline {
  agent any
  stages {
    stage('Buid') {
      steps {
        sh '''chmod 755 ./jenkins/test.sh
./jenkins/test.sh'''
        archiveArtifacts(artifacts: '/jenkins/*.jar', allowEmptyArchive: true, fingerprint: true)
        junit(testResults: '/jenkins/*.xml', allowEmptyResults: true)
      }
    }
  }
}