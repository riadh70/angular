pipeline {
  agent any
  
  stages {
    stage('Checkout') {
      steps {
        // Checkout your source code from the repository
        git 'https://github.com/riadh70/angular.git '
      }
    }
    
    stage('Build') {
      steps {
        // Install project dependencies and build the Angular app
        sh 'npm install'
        sh 'ng build --prod'
      }
    }
    

  }
}

