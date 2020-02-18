pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'hi test'
      }
    }

    stage('dev') {
      steps {
        sh 'hi dev'
      }
    }

    stage('prod') {
      steps {
        sh 'hi prod'
      }
    }

  }
  environment {
    t = ''
  }
}