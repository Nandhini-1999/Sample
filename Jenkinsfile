@Library('sh-lib') _

pipeline{
  agent any
  
  stages{
  stage('Build'){
      steps{
        script{
        build.call()
        }
      }
    }
    
    stage('Test'){
      steps{
        echo "mvn test"
      }
    }
    
  }
}
