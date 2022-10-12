pipeline {
	agent {
		docker {
			image 'zenika/alpine-chrome'
			args '-p 3000:3000'
		}
	}
	stages {
		stage('Build') {
			steps {
					sh 'node --version'
					//sh 'npm install'
					sh 'npm --version'
			}
		}
	}
}

