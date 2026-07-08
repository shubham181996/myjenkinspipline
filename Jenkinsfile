pipeline {

agent Docker-slave

stages {
	stage('SCM') {
		steps {
			echo "git pull the code"
			git 'https://github.com/shubham181996/simple-java-maven-app.git'
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
