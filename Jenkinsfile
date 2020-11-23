pipeline{
    agent any
    stages{
      stage('Build'){
          steps{
          echo 'Build Stage'
          }
      }
      stage('Test'){
          steps{
          bat 'mvn test'
          }
      }
      stage('DEPLOY'){
          steps{
          bat 'mvn deploy'
          }
      }

    }
}
