pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git 'https://github.com/jglick/simple-maven-project-with-tests.git'
      }
    }

  }
  environment {
    tools = 'maven'
  }
}