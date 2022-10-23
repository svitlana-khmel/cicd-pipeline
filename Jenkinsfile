pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''ls
node --version
npm install'''
      }
    }

    stage('Run tests') {
      steps {
        sh 'node --version'
      }
    }

  }
}