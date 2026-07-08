pipeline {

	agent {
		label 'Docker-slave'
	}

	stages {
		stage('SCM') {
			steps {
				echo "git pull the code"
				git 'https://github.com/shubham181996/simple-java-maven-app.git'
			}
		}	 

		stage('Build') {
			steps {
				sh 'mvn clean package'
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
