pipeline {
  agent any
  stages {
    stage('') {
      steps {
        parallel(
          "1": {
            sh 'echo \'1\''
            sh 'echo \'1\''
            
          },
          "2": {
            sh 'echo \'1\''
            
          }
        )
      }
    }
    stage('2') {
      steps {
        sh 'echo \'1\''
      }
    }
  }
}