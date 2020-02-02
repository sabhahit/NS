pipeline {
	agent any
	stages {
		stage ('1') {
			steps {
				echo "This is stage 1"	
			}	
		}
		stage ('2') {
			steps {
			echo "This is stage 2"	
			}
		}
		stage ('Integration Test') {
			agent {
				docker {
					image 'ubuntu'
				}
			}
			steps {
				echo "RRRRRRRRRRRRRRRRRRR"
			}
		}
	}
}	
			