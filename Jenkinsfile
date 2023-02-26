pipeline {
  agent {
    label 'docker-agent'
  }
  stages {
    stage('Build') {
      steps {
        sh 'Hello Build'
      }
    }
    
    stage('Test') {
      steps {
        sh 'Hello Test'
      }
    }
  }
}
