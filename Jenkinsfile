pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python3 hello_world.py'
      }
    }
     stage('wipro') {
      steps {
        sh 'python3 wipro.py'
      }
    }
     stage('jenkins') {
      steps {
        sh 'python3 Jenkins.py'
      }
    }
  }
}
