pipeline {
  agent any
  stages {
    stage ('Check out') {
      steps {
        git 'https://github.com/gladsonm934/simple-website.git'
      }
    }
    stage ('Build') {
      steps {
        echo 'Build the application'
      }
    }
    stage ('Test') {
      steps {
        echo 'Test the application'
      }
    }
    stage ('Deploy') {
      steps {
        echo 'Deploy the application'
      }
    }
  }
  post {
    success {
      echo 'Successfully completed'
    }
    failure {
      echo 'Failed to  up'
    }
  }
}
