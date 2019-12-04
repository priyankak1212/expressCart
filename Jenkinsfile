pipeline {
  agent any
  stages {
        
    stage('Cloning Git') {
      steps {
        git 'https://github.com/priyankak1212/expressCart'
      }
    }
 
    stage('Install dependencies') {
      steps {
        sh 'npm install'
      }
    }
     
    stage('Start') {
      steps {
         sh 'npm start'
      }
    }      
  }
}
