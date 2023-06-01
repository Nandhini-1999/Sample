@Library('sh-lib') _

pipeline{
  agent any
  
  stages{
  stage('Build'){
      steps{
        echo "mvn install"
      }
    }
    
    stage('Test'){
      steps{
        echo "mvn test"
      }
    }
    
  }
}
