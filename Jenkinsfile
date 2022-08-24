pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        echo 'THIS IS $BUILD_NUMBER FOR $DEMO'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}