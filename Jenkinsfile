pipeline {
    agent any
    tools {
        // Use the Go tool installed on your Jenkins server
        go 'Go'
    }
    environment {
        GO111MODULE = 'on'
        GIT_TIMEOUT = '600' // Set Git timeout to 10 minutes (600 seconds)
    }
    stages {
        stage('dev') {
            steps {
                // Since you're running on Windows, use the appropriate command to run tests
                bat 'go test ./...'
            }
        }
    }
}
