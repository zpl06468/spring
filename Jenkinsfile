pipeline {
  agent {
    node {
      label 'slave-01'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'echo \'Building\''
      }
    }

  }
  environment {
    a = '1'
  }
}