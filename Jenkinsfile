pipeline {
    agent any

    stages {
        stage('Build-test') {
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

>>>>>>> test
        stage('Deploy') {
            steps {
                echo "Deploying"
            }
        }    
    }   
}
