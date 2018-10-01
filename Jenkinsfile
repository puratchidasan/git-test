pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building'
        withMaven(maven : 'MyMaven'){
         bat 'mvn clean' 
        }        
      }
    }
  }
}
