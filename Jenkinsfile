pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('Mave') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}