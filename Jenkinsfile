@Library('sh-lib') _

pipeline{
  agent any
  
  stages{
  stage('Build'){
      steps{
        build()
      }
    }
    
    stage('Test'){
      steps{
        echo "mvn test"
      }
    }
    
  }
}
