pipeline {
  agent {
    docker {
      image 'node:15-alpine'
    }
  }
  stages {
    stage('build') {
      steps {
        sh 'npm --version'
        sh 'echo Hello-world'
      }
    }
  }
}
