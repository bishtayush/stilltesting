pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'This is Build Stage'
        bat 'mvn clean'
      }
    }

    stage('Test') {
      steps {
        echo 'This is Test Stage'
        bat 'mvn test'
      }
    }

    stage('Deploy') {
      steps {
        echo 'This is Deploy Stage'
        bat 'mvn package'
      }
    }

  }
}