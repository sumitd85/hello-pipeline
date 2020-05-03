pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'This is $BUILD_NUMBER for demo $DEMO'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}