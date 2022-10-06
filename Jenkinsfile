pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        script {
          docker ps
        }

      }
    }

  }
  environment {
    registry = 'alecjack/flask-app'
  }
}