
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Repository retrieved by Jenkins SCM'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Build stage are executed'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Test stage executed'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deploy stage executed'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully'
        }
        failure {
            echo 'Pipeline failed. Check console output.'
        }
    }
}
