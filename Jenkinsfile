pipeline {
  agent any
  stages {
    stage('Fluffy Build') {
      steps {
        sh 'echo Another Placeholder'
      }
    }

    stage('Fluffy Test') {
      steps {
        sh '''sleep 5
echo Success!'''
      }
    }

    stage('Fluffy Deploy') {
      steps {
        echo 'Fluffy Deployment'
      }
    }

  }
}