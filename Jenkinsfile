pipeline {
    agent none

    stages {
        stage('Build') {
            steps {
              nmp install
            }
        }
        stage('Unit-tests') {
            steps {
              npm run unit-test
              }
        
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
