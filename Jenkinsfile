

pipeline {

  agent any

 

  stages {

    
    stage('checkout') {
     
      
      steps {
         git 'https://github.com/SAKTHISIVANI18/sonar.git'
        
         }
    }

    stage('Static Code Analysis') {
  parallel {
    stage('Backend') {
      agent {
        label "node"
      }
      steps {
        sh "ls -al"
        }
      }
    }
    stage('Frontend') {
      agent {
        label "node"
      }
      steps {
          sh "ls -al"
        }
      }
    }
  }
}
  
