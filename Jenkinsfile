pipeline {
	agnet any
	stages {
		stage('Git Checkout') {
			steps {
				script {
				checkout scmGit(branches: [[name: '*/Main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github-cred', url: 'https://github.com/sumit-a1/java_app.git']])
				}
			}
		}
	}
}
