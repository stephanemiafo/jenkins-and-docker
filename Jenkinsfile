pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/stephanemiafo/jenkins-and-docker.git', branch: 'main')
      }
    }

    stage('log') {
      steps {
        sh 'Dir'
      }
    }

    stage('build') {
      steps {
        sh 'docker build -f Dockerfile .'
      }
    }

  }
}