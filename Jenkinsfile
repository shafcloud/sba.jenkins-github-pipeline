pipeline {
    agent { docker { image 'python:3.9.9' } }
    stages {
        stage('build') {
	    steps {
	        sh 'python web.py'
	    }
        }
    }
}
