pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code...'
                // This happens automatically if you link a Git repo
            }
        }
        stage('Build') {
            steps {
                echo 'Checking Python version...'
                sh 'python3 --version' 
            }
        }
        stage('Test/Run') {
            steps {
                echo 'Running the script...'
                sh 'python3 helloworld.py'
            }
        }
    }
}