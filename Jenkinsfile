pipeline {
    agent none

    stages {
        stage('Build') {
            steps {
              nmp install
            }
        }
        stage('Unit-test') {
            steps {
              npm run unit-test
              }
        }
        stage('Integration-test') {
            steps {
              npm run intergration-test
             }
        }

        stage('Deploy') {
            steps {
                echo "Deploying"
            }
        }    
    }   
}
