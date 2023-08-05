pipeline {
	agent any
	stages {
		stage('git repo & clean') {
			steps{
				script {
                    			try {
                				bat "git clone https://github.com/efsolora/PruebaJenkings"
                    }
                    			catch (ex) {
                        			bat "rm C:/ProgramData/Jenkins/.jenkins/workspace/pruebaJ"
                    }
                }
				
				
			}
		}

		stage('test') {
			steps{
				bat "cd C:/ProgramData/Jenkins/.jenkins/workspace/pruebaJ"
				bat "gradlew clean test aggregate"
			}
		}		
	}





}
