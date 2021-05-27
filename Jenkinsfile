pipeline {
  agent any
  stages {
    stage('Print') {
      parallel {
        stage('Print') {
          steps {
            sh 'echo "Hello World"'
          }
        }

        stage('') {
          steps {
            echo 'Hello World'
          }
        }

      }
    }

  }
}