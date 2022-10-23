pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''chmod +x -R ${WORKSPACE}
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.32.0/install.sh | bash

. ~/.nvm/nvm.sh

nvm install 4.4.5

node -v //4.4.5
./scripts/build.sh'''
      }
    }

    stage('Run tests') {
      steps {
        sh '''chmod +x -R ${WORKSPACE}
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.32.0/install.sh | bash

. ~/.nvm/nvm.sh

nvm install 4.4.5

node -v //4.4.5

./scripts/test.sh'''
      }
    }

  }
}