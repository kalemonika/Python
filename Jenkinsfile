
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
        sh 'python test.py'
        sh 'python tset1.py'
      }
    }
  }
}
