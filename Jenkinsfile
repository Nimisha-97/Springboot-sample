pipeline {
    agent any
    
    tools {maven 'mymaven'}
    
    stages {
       
       stage('Build') {
          steps {
              sh 'mvn clean install'
                }
            }
    }
}
