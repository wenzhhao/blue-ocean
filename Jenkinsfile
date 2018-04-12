pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'echo "test"'
      }
    }
    stage('deploy') {
      steps {
        sh 'echo "deploy" >/app/1.txt'
      }
    }
  }
}