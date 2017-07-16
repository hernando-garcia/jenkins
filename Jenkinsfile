pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
		sh 'sudo docker pull python:3.5.1'
                sh 'python --version'
            }
	}
        stage('Test') {
            steps {
		sh 'echo "Hello World of webhooks"'
            	}
	     }

        stage('Deploy') {
            steps {
		sh 'echo "Hello Deploy triggered by a webhook!"'
            	}	
             }
    	  }
}	
