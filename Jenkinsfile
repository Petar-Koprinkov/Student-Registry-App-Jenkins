pipeline {
    agent any
    
    stages {
        stage('Install dependencies') {
            steps {
                bat 'npm install'
            }
        }
        stage('Run test') {
            steps {
                bat 'npm run test'
            }
        }
    }
}