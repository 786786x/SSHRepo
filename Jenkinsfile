pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'python --version'
      }
    }
  }
  environment {
    stage = 'Build'
    image = 'python:3.5.1'
    sh = 'python --version'
  }
}