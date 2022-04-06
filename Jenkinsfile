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
                bat 'java Main hello'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}