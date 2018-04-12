library 'SharedLibs'
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
  stage('Shared Lib') {
         steps {
             helloWorld("Jenkins")
         }
      }
  }
}
