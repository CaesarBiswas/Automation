pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        sh '''echo "Hi test!"
go test ./...'''
      }
    }

  }
}