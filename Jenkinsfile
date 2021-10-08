pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'git@github.com:Reddy1202/staticRepository.git', branch: 'develop')
      }
    }

    stage('build') {
      steps {
        sh 'ls -ltr'
      }
    }

    stage('upload') {
      steps {
        sh 'ls'
      }
    }

    stage('deploy') {
      steps {
        sh 'ls'
      }
    }

  }
}