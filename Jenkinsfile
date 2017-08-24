pipeline {
  agent any
  stages {
    stage('Clean') {
      steps {
        sh 'mvn clean'
        sh 'echo "Hello Brant!"'
      }
    }
    stage('Install') {
      steps {
        sh 'mvn install'
      }
    }
    stage('site') {
      steps {
        sh 'mvn site'
      }
    }
  }
}
