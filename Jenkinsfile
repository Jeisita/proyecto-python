pipeline {
    agent any 
    
    stages {
        stage('Preparar entorno') {
            steps {
                sh 'python3 -m venv .venv'
                sh '.venv/bin/pip install pytest'
             }
         }
         
         stage('Pruebas') {
             steps {
                 sh '.venv/bin/pytest'
             }
          }
       }
    }

