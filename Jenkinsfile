pipeline {
  agent any
  stages {
    stage('Start') {
      steps {
        sh '''echo "Hello"
date
cal
hostname'''
      }
    }

    stage('Middle') {
      steps {
        sh 'echo "Hello all again"'
      }
    }

  }
}