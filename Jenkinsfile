pipeline {
    agent {
        docker { image 'python:3.9-slim' } 
    }
    stages {
        stage('Build') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('Test/Run') {
            steps {
                sh 'python3 helloworld.py'
            }
        }
    }
}