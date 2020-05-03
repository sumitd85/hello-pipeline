pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh '"This is $BUILD_NUMBER for demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}