pipeline {
    agent any //{ docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
                sh 'python3 main.py'
                echo 'webhook test - 3-th try'
            }
        }
    }
}
