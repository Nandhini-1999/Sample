@Library('sh-lib') _

pipeline{
  agent any
  
  stages{
  stage('Build'){
      steps{
        build.call()
      }
    }
    
    stage('Test'){
      steps{
        echo "mvn test"
      }
    }
    
  }
}
