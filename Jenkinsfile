@Library('my-shared-lib') _

pipeline {
	agent any
	stages {
		stage('Git Checkout') {
			steps {
				gitCheckout(
					branch: "Main",
					url: "https://github.com/sumit-a1/java_app.git"	
				)
			}
		}
		stage('Unit Test Maven') {
			steps {
				script {
					mvnTest()
				}	
			}
		}
	}
}
