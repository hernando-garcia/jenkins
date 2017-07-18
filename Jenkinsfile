pipeline {
    agent { sudo 'docker pull maven:3.3.3' }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
