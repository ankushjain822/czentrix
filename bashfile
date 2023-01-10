pipeline {
    agent {label 'linux'}
 
    stages {
        stage('hello') {
           steps {
               chmod +x '/var/lib/jenkins/workspace/bashscript-test/test.sh'
               sh '/var/lib/jenkins/workspace/bashscript-test/test.sh'
           }
        }
    }
}
