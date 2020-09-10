pipeline {
    agent any 
        
    stages {
        stage('Test') {
            steps {
                echo 'Hey Arjun Nikhil'
            }
        }
        stage('Version'){
            steps{
                script{
                    sh './python.py'
                }
            }
        }
	    stage("deploy") {
	        steps {
	        	echo 'Thanks for coming'
	        }
	    }
    }
}
