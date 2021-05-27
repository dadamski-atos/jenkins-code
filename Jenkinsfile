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

        stage('message') {
          steps {
            echo 'Hello World'
          }
        }

      }
    }

  }
}
