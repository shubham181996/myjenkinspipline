pipeline {

agent any

stages {
	stage('SCM') {
		steps {
			echo "git pull the code"
		}
	}	 

	stage('Deploy') {
		steps {
			echo "deploying my code"
		}
	}

	stage('Test') {
		steps {
			echo "Test my final webapp"
		}
	}
	stage('Deploy to PROD') {
		steps {
			echo "My final Webapp to prod"
		}
	}
}
}
