pipeline {
    agent {
        docker { image 'localhost:5000/node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
