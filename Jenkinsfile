pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Source code checked out from GitHub'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building Application...'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Running Tests...'
            }
        }
    }
}