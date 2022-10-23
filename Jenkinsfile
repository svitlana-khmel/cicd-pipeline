pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''ls
RUN ls
EXEC ls'''
      }
    }

    stage('Run tests') {
      steps {
        sh 'node --version'
      }
    }

  }
}