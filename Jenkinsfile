pipeline {
	agent any
	stages {
		stage('--------clean---------') {
			steps {
				sh "mavan clean"
			}
			
		}
		stage('------test------') {
			steps {
				sh "mvn test"
			}
		}
		stage('------package-------') {
			steps {
				sh "mvn package"
			}
		}
	}
}
