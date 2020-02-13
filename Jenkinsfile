pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'mvn clean'
        echo 'This is Build stage'
      }
    }

    stage('Test') {
      steps {
        bat 'mvn test'
        echo 'This is Test stage'
      }
    }

    stage('Deploy') {
      steps {
        bat 'mvn package'
        echo 'This is Deploy stage'
      }
    }

  }
}