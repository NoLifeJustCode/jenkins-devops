pipeline{
	agent any
	stages{
		stage('Build'){
			steps{
				echo "build"
			}
		}
		stage('test'){
			steps{
				echo "test"
			}
		}
		stage('iTest'){
			steps{
				echo "iTest"
			}
		}
	}
	post {
		always{
			echo "runs always"
		}
	}

}

