pipeline {
    agent none

    stages {
        stage('Build') {
            steps {
                sh "nmp install"
            }
        }
        stage('Unit-test') {
            steps {
                sh "npm run unit-test"
              }
        }
        stage('Integration-test') {
            steps {
                sh "npm run intergration-test"
             }
        }

        stage('Deploy') {
            steps {
                echo "Deploying"
            }
        }    
    }   
}
