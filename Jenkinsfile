pipeline {
	agent { podman { image 'python:3.10.1-alpine' } }
	stages {
		stage('build') {
			steps {
				sh 'python --version'
			}
		}
	}
}
