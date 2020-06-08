@Library('testdemo') _
pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'hello world'
        script{
         test.envname()
        }
      }
    }

  }
}
