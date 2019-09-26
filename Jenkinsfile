pipeline {
    agent any

    tools {nodejs "NodeJS 12.11.0"}
    
    environment {
        CI = 'true' 
    }
    
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
        stage('Deliver') { 
            steps {
                sh './scripts/deliver.sh' 
            }
        }
    }
}