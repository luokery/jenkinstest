pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            sleep(time: 10, unit: 'SECONDS')
          }
        }

        stage('bb') {
          steps {
            sh 'ls'
          }
        }

      }
    }

  }
}