pipeline {
  agent any

  stages {
    stage('compile') {
      steps {
        bat 'javac Test.java'
      }
    }

    stage('run') {
      bat 'java Test'
    }
  }
}
