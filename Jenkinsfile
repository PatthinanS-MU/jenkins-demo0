pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Checking Python version...'
                sh 'python3 --version'
            }
        }
        stage('Run Script') {
            steps {
                echo 'Executing helloworld.py...'
                sh 'python3 helloworld.py'
            }
        }
    }
}