pipeline {
  agent {
    node {
      label 'node1'
    }

  }
  stages {
    stage('Step1') {
      steps {
        sh 'echo "stage1"'
      }
    }

  }
  environment {
    var1 = 'hello'
  }
}