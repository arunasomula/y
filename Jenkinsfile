pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        sh 'echo "Hello world!"'
        sh 'echo "dev"'
      }
    }
    stage('build') {
      steps {
        echo 'building '
      }
    }
    stage('test') {
      steps {
        echo 'test'
      }
    }
  }
}