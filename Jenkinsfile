pipeline {
  agent any
      tools {
        maven 'Maven' // Replace 'M3' with the name of your configured Maven tool in Jenkins
    }
  stages {
    stage('Build') {
      steps {
        sh 'mvn -Dmaven.test.failure.ignore=true clean deploy'
      }
    }

  }
}
