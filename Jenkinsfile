pipeline {
	agent {
		docker {
			image 'node:9.8'
		}
	}
	stages {
		stage('Build') {
			steps {
				echo 'Building...'
				sh 'npm install'
			}
		}
	}
}
