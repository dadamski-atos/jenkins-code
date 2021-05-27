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

        stage('newCommint') {
          steps {
            echo 'To jest nowy komin'
          }
        }

      }
    }

  }
}
