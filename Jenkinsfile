pipeline {
    agent any
    stages {
        stage('hello') {
            steps {
                sh 'echo Hello Jenkins!'
            }
        }
        stage('Build Docker') {
            steps {
                sh 'docker build -t node-api ./webapi/Dockerfile'
            }
        }
    }

}

