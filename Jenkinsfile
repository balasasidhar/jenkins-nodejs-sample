pipeline {
    agent any

    tools {nodejs "NodeJS 12.11.0"}
    
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}