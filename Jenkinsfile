pipeline {
    agent {
        docker { image 'node:16.13.1-alpine' }
    }
    stages {
        stage('Build') {
            steps {
                "javac Main.java"
                
            }
        }
        stage('Test') {
            steps {
                "java Main 1 2 3"
                
            }
        }
    
    }
}