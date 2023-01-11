pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3.9 --version'
      }
    }
  stage('hello') {
    steps {
      sh 'python3.9 hello.py'
      sh 'python3.9 message.py'
      }
    }
  }
} 
