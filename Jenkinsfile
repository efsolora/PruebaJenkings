pipeline {
	agent any
	stages {
		stage('git repo & clean') {
			steps{
				sh "https://github.com/efsolora/PruebaJenkings"
				cd "C:\ProgramData\Jenkins\.jenkins\workspace\pruebaJ"
			}
		}

		stage('test') {
			steps{
				sh "gradlew clean test aggregate"
			}
		}		
	}





}
