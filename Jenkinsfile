pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Smoke Test') {
            steps {
                sh 'node --version'
                sleep 10
            }
        }
    }
}