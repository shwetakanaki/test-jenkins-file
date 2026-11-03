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
            sh 'docker run -it demo:t3'
            }
        }
         
    }
}
