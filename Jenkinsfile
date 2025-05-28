pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '$MVN_HOME/bin/mvn" -Dmaven.test.failure.ignore clean deploy'
      }
    }

  }
}