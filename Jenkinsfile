@Library('testdemo') _
pipeline {
  agent any
  environment{
  name=test.envname()
  }
  stages {
    stage('test') {
      steps {
        echo "hello new world $name"
        echo hello
      
      }
    }

  }
}
