pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                bat 'python --version'
            }
        }
        stage('First Program') {
            steps {
                bat 'python test.py'
            }
        }

        stage('Second Program') {
            steps {
                bat 'python test2.py'
            }
        }
    }
}
