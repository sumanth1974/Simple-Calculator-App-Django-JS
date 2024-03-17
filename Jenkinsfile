pipeline {
  agent any
  stages {
    stage('build') {
      agent any
      steps {
        sh 'echo "hello, i am trying to build"'
      }
    }

  }
  environment {
    env = 'dev'
  }
}