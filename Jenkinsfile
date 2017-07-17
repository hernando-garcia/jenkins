pipeline {
    agent { docker 'python:3.5.1' }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'python -c 'import boto3'
                sh 'python -c 'import boto'
            }
        }
    }
}
