pipeline {
    agent any 
        
    stages {
        stage('Test') {
            steps {
                echo 'Hey Arjun'
            }
        }
        stage('Version'){
            steps{
                script{
                    sh 'helloworld.py'
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
