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
        archiveArtifacts(artifacts: '/jenkins/*.xml', allowEmptyArchive: true, caseSensitive: true, fingerprint: true)
      }
    }
  }
}