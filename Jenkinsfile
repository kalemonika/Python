
pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python3 --version'
      }
    }
    stage('TEST') {
      steps {
         bat 'python test.py'
        
      }
    }
  }
}
