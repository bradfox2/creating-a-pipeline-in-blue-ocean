pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '''-p 3000:3000
--privileged'''
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