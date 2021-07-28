pipeline {
	agent any
	triggers {
		cron(' * * * * * ')
	}
	stages { 
		stage('Build') {
			steps {
			      echo 'build the application'
			}
		}
	
		stage('deploy') {
			steps {
			      
				echo 'deploy the application'
			}
        }
		
		stage('Test') {
			steps {
			      
				echo 'testing the application'
			}
        }
	}
	
}
