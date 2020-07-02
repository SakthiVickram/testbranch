@Library('testdemo') _
pipeline {
  agent any
  environment{
  name=test.envname()
  }
  stages {
    stage('test') {
      steps {
         println test.checkBranchIndexing()
        println currentBuild.rawBuild.getBuildCauses()
        echo "hello existing world $name"
        echo "from dev2"

      
      }
    }

  }
}
