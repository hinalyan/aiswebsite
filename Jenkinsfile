pipeline {
  agent {
    docker {
      image 'docker'
    }

  }
  stages {
    stage('build') {
      steps {
        build 'job'
      }
    }
  }
  environment {
    npm = 'npm'
  }
}