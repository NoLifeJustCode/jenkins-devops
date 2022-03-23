pipeline{
	agent { docker { image  "node:latest" }}
	stages{
		stage('Build'){
			steps{
				sh 'node --version'
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
		failure {
			echo "failed to run pipeline"
		}
	}

}

