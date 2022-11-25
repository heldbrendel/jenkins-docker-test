pipeline {
  agent any
  options {
    buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '', daysToKeepStr: '', numToKeepStr: '1')
  }
  tools {
    gradle 'Gradle'
  }
  stages {
    stage('Test') {
      steps {
        sh 'gradle --version'
      }
    }
  }
}