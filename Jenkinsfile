pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building...'
          }
        }

        stage('Build2') {
          steps {
            echo 'Building2...'
          }
        }

        stage('Build3') {
          steps {
            echo 'Building3...'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Testing...'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying...'
      }
    }

  }
}