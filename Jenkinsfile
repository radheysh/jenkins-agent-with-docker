pipeline {
  agent {
    docker {
      image 'node:16-alpine'
      args 'PATH = "/usr/bin/docker"'
    }

  }
  stages {
    stage('checkout') {
      steps {
        sh 'Jenkinsfile-1'
      }
    }

  }
}