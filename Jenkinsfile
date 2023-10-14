pipeline {
  agent any

  triggers {
    githubPush()
  }

  stages {
    stage('checkout') {
      steps {
            //checkout the repository
          checkout scm
      }
    }
  }
