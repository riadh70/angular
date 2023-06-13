pipeline {
  agent any
  
  stages {
    stage('Checkout') {
      steps {
        // Checkout your source code from the repository
        git 'https://github.com/riadh70/angular.git '
      }
    }
    
 pipeline {
  agent any
  
  stages {
    stage('Build') {
      steps {
        sh '''
        export PATH=$PATH:/root/.nvm/versions/node/v12.22.12/bin
        npm install
        '''
      }
    }
  }
}

    

  }
}

