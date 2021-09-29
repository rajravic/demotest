pipeline {
  agent any
  stages{
    stage('Build'){
      steps{
        echo 'Buliding the application'
        sh 'sh buildflow.groovy'
        }
    }
    stage("Test"){
      steps{
          echo 'Testing the application'
        }
    }
    stage("Deploy"){
       steps{
           echo 'Deploying the application'
       }
    }
  }
}
