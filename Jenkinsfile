pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('First Stage') {
      agent any
      steps {
        echo "Hello ${MY_NAME}!"
        sh '''java -version
'''
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}