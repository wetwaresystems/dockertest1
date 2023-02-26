pipeline {
  agent {
    docker { image 'docker-agent' }
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
