pipeline {
    agent any 
    
    stages {
        stage('Instalar pytest') {
            steps {
                sh 'python3 -m pip install --user pytest'
             }
         }
         
         stage('Pruebas') {
             steps {
                 sh 'pytohon3 -m pytest'
             }
          }
       }
    }

