pipeline {
    agent any 
        
    stages {
        stage('Test') {
            steps {
                echo 'Hello world'
            }
        }
        stage('Version'){
            steps{
                script{
                    echo "versionpy"
                }
            }
        }
	    stage("deploy") {
	        steps {
	        	echo 'Deploy success'
	        }
	    }
    }
}
