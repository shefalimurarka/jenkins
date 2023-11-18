pipeline {
  agent any
  stages {
    stage('Buld') {
      steps {
        bat 'Hello world'
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'test'
          }
        }

        stage('prod') {
          steps {
            echo 'prod'
          }
        }

      }
    }

  }
}