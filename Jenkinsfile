pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('First Stage') {
      agent any
      steps {
        echo "Hello ${MY_NAME}!"
        sh '''java -version
'''
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
    TEST_USER = credentials('test-user')
  }
}