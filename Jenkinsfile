@Library('sh-lib') _

pipeline{
  agent any
  
  stages{
  stage('Build'){
      steps{
        script{
        build()
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
