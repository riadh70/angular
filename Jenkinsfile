pipeline {
  agent any 
  
   environment {
    PATH = "/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/root/.nvm/versions/node/v12.22.12/bin"
  }
  
  stages {
    stage('Checkout') {
      steps {
        // Checkout your source code from the repository
        git 'https://github.com/riadh70/angular.git '
      }
    }
     
 
    stage('Build') {
      steps {
            sh 'npm install'
      }
    }
  


    

  }
}

