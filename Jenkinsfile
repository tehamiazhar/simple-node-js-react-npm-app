pipeline {
    agent {
        docker {
	    sh 'sudo docker pull node:6-alpine'
            image 'node:6.14.3-alpine'
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}


