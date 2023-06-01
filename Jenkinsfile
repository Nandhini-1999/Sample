pipeline{
  agent any
  
  stages{
    //stage('Checkout') {
     //steps{
        //git credentialsId: 'jyothi', url: 'git@github.com:jyothiswaroopreddy08/devops-project.git'
      //}
     //}
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
