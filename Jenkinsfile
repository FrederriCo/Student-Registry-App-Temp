pipeline {
    agent any 
    stages {
        stage('NPM Install') { 
            steps {
                bat 'npm install'
            }
        }
        stage('NPM Audit') { 
            steps {
                bat 'npm audit'
            }
        }
        stage('Run Test') { 
            steps {
                bat 'npm run test'
            }
        }
        stage('Deploy to production') { 
            steps {
                bat 'Deploying .......'
            }
        }            
    }
}