pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t cicd-demo .'
            }
        }

        stage('Stop Old Container') {
            steps {
                sh '''
                docker stop cicd-demo || true
                docker rm cicd-demo || true
                '''
            }
        }

        stage('Run Container') {
            steps {
                sh 'docker run -d --name cicd-demo -p 8080:80 cicd-demo'
            }
        }
    }
}
