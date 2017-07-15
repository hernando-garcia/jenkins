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
		sh 'echo "Hello World"'
            	}
	     }

        stage('Deploy') {
            steps {
		sh 'echo "Hello Deploy!"'
            	}	
             }
    	  }
}	
