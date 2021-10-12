pipeline {
  agent {
    node {
      label 'node1'
    }

  }
  stages {
    stage('Step1') {
      parallel {
        stage('Step1') {
          steps {
            sh 'echo "stage1"'
          }
        }

        stage('step2') {
          steps {
            sh 'echo "fun with blue ocean"'
          }
        }

      }
    }

  }
  environment {
    var1 = 'hello'
  }
}