pipeline{
    agent any
    stages{
      stage('Start'){
          steps{
          echo 'Start the pipeline'
          }
      }
      
      stage('Clean'){
          steps{
            bat 'mvn clean'
          }
      }
      
      stage('Install'){
          steps{
            bat 'mvn install'
          }
      }
    }
}
