pipeline {
    agent any

    stages {
        stage('Set up') {
            steps {
                echo 'Hello World'
            }
       } 
       
       stage('Building') {
            steps {
                echo 'Building Phase'
            }
       } 
    
       stage('Testing') {
            steps {
                echo 'Testing Phase1'
            }
       }
    }

} 
