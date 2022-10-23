pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh './scripts/build.sh'
      }
    }

    stage('Run tests') {
      steps {
        sh 'node --version'
      }
    }

  }
}