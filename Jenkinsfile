pipeline {
  agent {
    docker {
      image 'redis:alpine'
      args '-p 6379:6379'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'echo \'redis\''
      }
    }
  }
}