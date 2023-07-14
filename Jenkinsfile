pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        dir('./jenkins') {
           // sh "chmod +x gradlew"
           // sh  "./gradlew clean build --info"
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
