pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:6.14.3'
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