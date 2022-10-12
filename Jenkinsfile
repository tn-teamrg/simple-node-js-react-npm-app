pipeline {
	agent {
		docker {
			// image 'centos' // original image -- EOL
			// image 'node:lts-bullseye-slim'
			// image 'zenika/alpine-chrome'
			image 'lts-alpine3.15'
			args '-p 3000:3000'
		}
	}
	stages {
		stage('Build') {
			steps {
					echo 'node version: '
					sh 'node --version'

					echo 'npm version: '
					sh 'npm --version'
					// sh 'npm install'
			}
		}
	}
}

