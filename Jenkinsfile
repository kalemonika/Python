pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                echo 'python --version'
            }
        }
        stage('hello') {
            steps {
                bat 'python test.py'
            }
        }
    }
}
