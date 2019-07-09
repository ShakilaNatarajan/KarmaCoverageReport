pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
    stage('Test and coverage') {
      steps {
        sh 'npm test'
      }
    }
  }
}