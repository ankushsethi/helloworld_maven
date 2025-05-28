pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'sh \'"$MVN_HOME/bin/mvn" -Dmaven.test.failure.ignore clean deploy\''
      }
    }

  }
}