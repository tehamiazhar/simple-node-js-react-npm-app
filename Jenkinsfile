pipeline {
    agent {
        docker {
            image 'node:6.14.3-alpine'
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
               	sh 'cd src'
                sh 'npm install'
                sh 'npm start'
            }
        }
    }
}


