pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'this is build number $BUILD_NUMBER  for a job called $Demo'
      }
    }

  }
  environment {
    Demo = '1'
  }
}