pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh 'node server.js' 
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'make publish'
            }
        }
    }
}