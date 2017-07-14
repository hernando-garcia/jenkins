pipeline {
    agent any
    stages {
        stage('build') {
            steps {
		sh 'sudo docker pull python:3.5.1'
                sh 'python --version'
            }
        }
    }
}
