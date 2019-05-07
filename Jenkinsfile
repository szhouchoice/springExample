pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''mv clean
'''
      }
    }
    stage('Test') {
      steps {
        sh 'mvn test'
      }
    }
    stage('Deploy') {
      steps {
        sh 'mvn package'
      }
    }
  }
}