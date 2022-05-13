pipeline {
	environment {
        	dockerimagename = "chuprasa/nodeapp"
                dockerImage = ""
	}
	agent any
	stages {	
    		stage ('Checkout Git Source Code') {
	    		git branch: 'main', credentialsId: 'github', url: 'https://github.com/chuprasa/nodejsapp.git'
		}
	}
}
