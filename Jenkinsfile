node {
    environment {
        dockerimagename = "chuprasa/nodeapp"
        dockerImage = ""
    }
    stage ('Checkout Git Source Code') {
	    git branch: 'main', credentialsId: 'github', url: 'https://github.com/chuprasa/nodejsapp.git'
	}
}
