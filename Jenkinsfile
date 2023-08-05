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
				sh  "C:/ProgramData/Jenkins/.jenkins/workspace/pruebaJ"
				sh "gradlew clean test aggregate"
			}
		}		
	}





}
