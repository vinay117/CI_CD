pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        dir('./jenkins') {
            // bat "chmod +x gradlew"
            bat  "gradlew clean build --info"
        }
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}
