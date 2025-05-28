pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn -X -Dmaven.test.failure.ignore=true clean deploy'
      }
    }

  }
  tools {
    maven 'Maven'
  }
}