pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/devopsdeepdive/test-pipeline.git', branch: 'master', credentialsId: 'github_passwd')
      }
    }

  }
}