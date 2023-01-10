pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python2 --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python2 hello.py'
      }
    }
  }
} 
