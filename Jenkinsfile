pipeline {
  agent any
  stages {
    stage('Clean') {
      steps {
        sh 'mvn clean'
        sh 'echo "Hello Brant!"'
        sh 'pwd'
        sh '(exit 9)'
        sh 'hostname'
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
