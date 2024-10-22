/* Requires the Docker Pipeline plugin */
pipeline {
    agent { dockerContainer { image 'python:3.13.0-alpine3.20' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}