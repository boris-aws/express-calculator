pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building"
            }
        }
        stage('Unit/integration tests') {
            steps {
                "./node_modules/.bin/jest src/__tests__/unit"
              }
        }
            steps {
                "./node_modules/.bin/jest src/__tests__/integration"
             }
        
        stage('Deploy') {
            steps {
                echo "Deploying"
            }
        }    
    }   
}
