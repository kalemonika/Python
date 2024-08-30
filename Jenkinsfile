
pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('TEST') {
      steps {
        sh 'python3 test.py'
        sh 'python3 tset1.py'
      }
    }
  }
}
