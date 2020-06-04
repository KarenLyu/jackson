pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'start build'
        sh 'echo "build step"'
      }
    }

    stage('test') {
      steps {
        echo 'test stage'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy stage'
      }
    }

  }
}