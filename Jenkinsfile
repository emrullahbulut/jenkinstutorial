pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'javac Main.java'
            }
        }
        stage('Run') {
            steps {
                bat 'java Main 1'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}