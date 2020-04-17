

pipeline {

  agent any

 

  stages {

    
    stage('checkout') {
     
      
      steps {
         git 'https://github.com/SAKTHISIVANI18/sonar.git'
        
         }
    }

    // Static Code Analysis
    stage('Static Code Analysis') {
      
      
      steps {
        sh "echo 'Run Static Code Analysis'"
      }
    }

   

    
  }
}
