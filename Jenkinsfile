pipeline{
  agent any 
  stages{
    stage('clone'){
      steps{
        git branch:'main',url:https://github.com/srikanthdasa/Calculator.git
          }
    }
    stage('compile'){
      steps{
        sh'javac claculator.java'
      }
    }
    stage('build'){
      steps{
        sh'java calculator 25 5'
      }
    }
  }
}
