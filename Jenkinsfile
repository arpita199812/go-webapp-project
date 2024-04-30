pipeline {
  agent any
  tools {
      go 'Go'
  }
  environment {
      GO111MODULE = 'on'
  }
  stages {
    stage('dev') {
      steps {
        sh 'go test ./...'
      }
    }

  }
}
