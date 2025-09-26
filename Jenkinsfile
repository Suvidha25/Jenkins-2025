pipeline {
    agent none 
    stages {

        stage ('SCM Checkout') {
           agent {
              label 'slave1'
           }
            steps {
                echo 'This is first step'
            }
        }

        stage ('Build') {
           agent {
              label 'slave2'
           }
            steps {
                sh '''
                   pwd
                '''
            }
        }
    }
}  