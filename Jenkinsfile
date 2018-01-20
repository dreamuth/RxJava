pipeline {
  agent any
  stages {
    stage('Clean') {
      steps {
        sh './gradlew clean'
      }
    }
    stage('Build') {
      steps {
        sh './gradlew build'
      }
    }
    stage('Check') {
      steps {
        sh './gradlew check'
      }
    }
  }
}