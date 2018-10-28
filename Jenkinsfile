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
        echo 'hi'
        sleep 1
        node(label: 'abc') {
          echo 'done'
        }

      }
    }
  }
  environment {
    modela = '1'
  }
}