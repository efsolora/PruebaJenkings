pipeline {
	agent any
	stages {
		stage('git repo & clean') {
			steps{
				bat "git clone https://github.com/efsolora/PruebaJenkings"
				
			}
		}

		stage('test') {
			steps{
				bat " cd C:/ProgramData/Jenkins/.jenkins/workspace/pruebaJ"
				bat "gradlew clean test aggregate"
			}
		}		
	}





}
