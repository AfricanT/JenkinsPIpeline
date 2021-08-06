pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'I want to sheesh. '
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'I want to test.'
          }
        }

        stage('Deploy') {
          steps {
            echo 'Deployed'
          }
        }

      }
    }

  }
}