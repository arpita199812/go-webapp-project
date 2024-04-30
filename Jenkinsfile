pipeline {
  agent any
  tools {
      Go '1.11.4'
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
