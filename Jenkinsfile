pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Fetching source code from GitHub'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application'
            }
        }

        stage('Docker Build') {
            steps {
                echo 'Building Docker image'
            }
        }

        stage('Docker Push') {
            steps {
                echo 'Pushing Docker image'
            }
        }

    }

    post {
        success {
            echo 'Pipeline completed successfully'
        }
        failure {
            echo 'Pipeline failed'
        }
    }
}
