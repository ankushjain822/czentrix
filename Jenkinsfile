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
      sh 'python3.9 Python_Script_hello.py'
      }
    }
  }
} 
