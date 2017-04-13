pipeline {
  agent any
  stages {
    stage('') {
      steps {
        parallel(
          "1": {
            sh 'echo \'1\''
            
          },
          "2": {
            sh 'echo \'2\''
            
          }
        )
      }
    }
    stage('3') {
      steps {
        sh 'echo \'3\''
      }
    }
  }
}