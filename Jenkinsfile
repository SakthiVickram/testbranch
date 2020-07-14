@Library('testdemo') _
if(test.checkBranchIndexing()){
   // error('Some error text')

    return
}
pipeline {
  agent any
  environment{
  name=test.envname()
  }
  stages {
    stage('test') {
      steps {
         println test.checkBranchIndexing()
        println test.info("hii again test pr2")
        echo "hello existing world $name"
        echo "from dev2"

      
      }
    }

  }
}
