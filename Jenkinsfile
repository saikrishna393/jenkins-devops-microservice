pipeline{
	agent {docker {image 'maven:3.6.3'}}
	stages {
		stage('mvn') {
			steps{
				sh 'mvn --version'
				echo "Build"
			}
		}
		stage('Build') {
			steps {
			  echo "Build"
		    }
		}
		stage('Test') {
			steps{
				echo "Test"
			}
		}
	}
}


	

