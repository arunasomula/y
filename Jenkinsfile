pipeline {
  agent any
  stages {
    stage('dev') {
      parallel {
        stage('dev') {
          steps {
            sh 'echo "Hello world!"'
            sh 'echo "dev"'
          }
        }
        stage('git checkout') {
          steps {
            echo 'git '
          }
        }
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