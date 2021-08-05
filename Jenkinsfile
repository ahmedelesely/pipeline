pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Hello Building'
      }
    }

    stage('test') {
      steps {
        sh 'echo $(pwd)'
      }
    }

  }
}