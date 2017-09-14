pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        sh 'echo "hello world"'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
        sleep 1
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}