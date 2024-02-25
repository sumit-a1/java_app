<<<<<<< HEAD
@Library('my-shared-lib') _

=======
>>>>>>> origin/Main
pipeline {
	agent any
	stages {
		stage('Git Checkout') {
			steps {
				script {
<<<<<<< HEAD
					gitCheckout {
						branch: "main"
						url: "https://github.com/sumit-a1/java_app.git"
						
					}
=======
				checkout scmGit(branches: [[name: '*/Main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github-cred', url: 'https://github.com/sumit-a1/java_app.git']])
>>>>>>> origin/Main
				}
			}
		}
	}
}
