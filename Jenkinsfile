pipeline {
  agent any
  stages {
    stage('Fluffy Build') {
      steps {
        sh '''chmod 777 build.sh
build.sh'''
      }
    }

    stage('Fluffy Test') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

    stage('Fluffy Deploy') {
      steps {
        sh './jenkins/deploy.sh'
      }
    }

  }
}