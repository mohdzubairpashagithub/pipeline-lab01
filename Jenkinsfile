pipeline {
  agent any
  stages {
    stage('Fluffy Build') {
      steps {
        echo 'Fluffy Building'
        sh 'echo Another Placeholder'
      }
    }

    stage('Fluffy Test') {
      steps {
        echo 'Fluffy Testing'
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