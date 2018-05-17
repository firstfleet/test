pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''echo test
npm -v
node -v
pm2 -v
$PATH'''
      }
    }
  }
}