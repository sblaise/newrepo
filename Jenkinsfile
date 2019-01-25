pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo \'yo\''
          }
        }
        stage('') {
          steps {
            mail(subject: 'new mail', body: 'blablabla', to: 'toto@amadeus.com')
          }
        }
      }
    }
  }
}