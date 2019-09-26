pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build is successful'
          }
        }
        stage('Build2') {
          steps {
            echo '1'
          }
        }
        stage('Build3') {
          steps {
            echo '2'
          }
        }
        stage('Build4') {
          steps {
            echo '3'
          }
        }
      }
    }
    stage('Test') {
      steps {
        echo 'Testing is done'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deployed successfully'
      }
    }
  }
}