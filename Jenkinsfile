pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''chmod +x -R ${env.WORKSPACE}
./scripts/build.sh'''
      }
    }

    stage('Run tests') {
      steps {
        sh 'node --version'
      }
    }

  }
}