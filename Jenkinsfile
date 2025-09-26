pipeline {
    agent none 
    stages {

        stage ('SCM Checkout') {
           agent {
              label 'slae1'
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