pipeline {
  agent any
  stages {
    stage('NewJourney') {
      parallel {
        stage('NewJourney') {
          steps {
            echo 'dippity Duuurp!'
          }
        }
        stage('Step2') {
          steps {
            echo 'I\'m doing something....'
          }
        }
        stage('') {
          steps {
            bat(returnStatus: true, returnStdout: true, script: 'c:\\temp\\test.btm')
          }
        }
      }
    }
  }
  environment {
    OS = 'Win10x64'
  }
}