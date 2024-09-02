pipeline {
    agent any

    stages {
        stage('Version') {
            steps {
                sh 'python3 Version'
            }
        }
        
        stage('RUN PYTHON FILE') {
            steps {
                
                 sh 'python3 test2.py'
            }
        }
        
        
    }
}

