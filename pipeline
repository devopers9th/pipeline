pipeline {
    agent { label 'slave3'}
      stages {
        stage ('Git') {
          steps {
            script {
              checkout scm
              }
            }
         }  
          stage ('report') {
           steps {
            script {
              "WELCOME"
            }
          }
         }
   }
 }  
