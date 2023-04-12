pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        build()
        echo 'Hello Build'
        echo 'Test code'
      }
    }

  }
  environment {
    name = 'build'
  }
}