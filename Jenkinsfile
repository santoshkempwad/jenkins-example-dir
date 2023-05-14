pipeline {
  agent any
  stages {
    stage('full path') {
      steps {
        sh 'cat my-project/name.txt'
      }
    }
    stage('use dir') {
      steps {
        dir('my-project') {
          sh 'cat name.txt'
        }
      }
    }
  }
}
