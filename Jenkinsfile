pipeline {
    agent {
        docker {
            image 'node:6.14.3-alpine'
            args '-u root:root' 
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


