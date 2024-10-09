pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Initial build'
          }
        }

        stage('Test') {
          steps {
            echo 'testing the pipeline source code'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying the code to server'
      }
    }

  }
}