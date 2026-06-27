pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Source code checked out from GitHub'
            }
        }

        stage('Build Docker Image') {
            steps {
                bat 'docker build -t devops-demo:v1 .'
            }
        }

        stage('Run Docker Container') {
            steps {
                bat 'docker run --rm devops-demo:v1'
            }
        }
    }
}