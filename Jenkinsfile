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
            echo 'That\'s It! You\'re grounded!'
          }
        }
      }
    }
  }
  environment {
    OS = 'Win10x64'
  }
}