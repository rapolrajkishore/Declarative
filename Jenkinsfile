pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello %NAME%'
      }
    }
    stage('Test') {
      steps {
        bat 'echo %NAME%'
      }
    }
  }
}