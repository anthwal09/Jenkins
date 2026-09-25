pipeline {
    agent any
    stages {
        stage('Build & Test') {
            steps {
                echo 'Running python script on Windows...'
                bat 'python hello.py'
            }
        }
    }
}