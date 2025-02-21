pipeline{
    agent any 
    
  stages {
      stage ('Git Checkout'){
        steps {
            git branch: 'main', url: 'https://github.comm/eyaaabaab/Jenkins-atelier.git'
          }
      }
      
      stage('complie'){
          steps {
              sh 'mvn clean compile'
            }
        }
    }
}
