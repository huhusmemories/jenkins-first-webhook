pipeline {
    agent any
    stages {
        stage("build"){
	    steps{
	        sh "echo Integrating Jenkins pipeline with github webhook using jenkinsfile"
                sh "ls"
                sh "python3 --version"
                sh "python3 pipeline.py"
		}
            }
	}
}
