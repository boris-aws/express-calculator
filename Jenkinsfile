pipeline {
    agent none

    stages {
        stage('Build') {
            steps {
                npm install
            }
        }
        stage('Unit-test') {
            steps {
                npm run unit-test
            }
        }
        stage('Integration-test') {
            steps {
                npm run integration-test
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
    }
}
}