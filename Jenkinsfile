pipeline {
  agent any
  stages {
    stage('Checkout main branch') {
      steps {
        git branch: 'main', url: 'https://github.com/islamJamer/createPipeline.git'
      }
    }

    stage('Test') {
      steps {
        echo 'Test'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }
  }
}