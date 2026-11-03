pipeline {
    agent any

    stages {
        stage('build') {
            steps {
               sh 'docker build -t demo:t3 .'
            }
        }
        
        stage('run') {
            steps {
            sh 'docker run -d demo:t3'
            }
        }
         
    }
}
