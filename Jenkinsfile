@Library('testdemo') _
pipeline {
  agent any
  environment{
  name=test.envname()
  }
  stages {
    stage('test') {
      steps {

        echo "hello existing world $name"
        echo "from dev2"

      
      }
    }

  }
}
