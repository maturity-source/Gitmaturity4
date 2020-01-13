pipeline {
  agent any
  stages {
    stage('build 1') {
      agent any
      steps {
        echo 'lkljkjk'
      }
    }

    stage('error') {
      steps {
        sh 'jenkins/build.bat'
      }
    }

  }
}