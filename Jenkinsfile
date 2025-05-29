pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn -X -Dmaven.test.failure.ignore=true clean deploy -s /var/jenkins_home/workspace/helloworld_maven_master/settings.xml'
      }
    }

  }
  tools {
    maven 'Maven'
  }
}
