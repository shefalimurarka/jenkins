pipeline {
  agent any
  stages {
    stage('Buld') {
      steps {
        echo 'test'
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