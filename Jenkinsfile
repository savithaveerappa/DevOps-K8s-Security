pipeline {
  agent any
  stages {
    stage ('Build and analyze') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}
