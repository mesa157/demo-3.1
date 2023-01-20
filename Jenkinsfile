pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo "this isbuild number $BUILD_NUMBER OF $Demo job"'
      }
    }

  }
  environment {
    Demo = '1'
  }
}