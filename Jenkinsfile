pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'This is the first step of the pipeline'
        sleep 5
      }
    }
    stage('Testing') {
      steps {
        echo 'Running tests'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying artifact to Artifactory'
      }
    }
  }
}