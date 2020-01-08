pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:6.14.3-alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
}