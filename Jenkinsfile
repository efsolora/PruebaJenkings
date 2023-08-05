pipeline {
	agent any
	stages {
		stage('git repo & clean') {
			steps{
				sh "https://github.com/efsolora/PruebaJenkings"
			}
		}

		stage('test') {
			steps{
				sh ".\gradlew clean test aggregate"
			}
		}		
	}





}
