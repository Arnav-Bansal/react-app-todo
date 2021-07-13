pipeline {
  agent any
    
  tools {nodejs "node"}
    
  stages {
       
     
    stage('Build') {
      steps {
       bat 'npm clean-install'
       bat 'npm run build'
       bat 'C:\Users\Dell\Documents\GitHub\react-todo-app-sample'
       bat 'docker build -t arnav/react-app .'
      }
    }
  }
}
