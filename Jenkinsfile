pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('First Stage') {
      agent any
      steps {
        echo 'Hello World'
        sh '''java -version
'''
      }
    }
  }
}