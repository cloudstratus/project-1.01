pipeline {
  agent {
    node {
      label 'abc'
    }

  }
  stages {
    stage('test') {
      steps {
        sh 'cat abc'
      }
    }
  }
  environment {
    modela = '1'
  }
}