pipeline {
	agent {
		docker {
			image 'alpine:3.15'
			args '-p 3000:3000'
		}
	}
	stages {
		stage('Build') {
			steps {
					sh 'node --version'
					sh 'npm --version'
			}
		}
	}
}