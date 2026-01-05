pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/Adiparihar/jenkins-docker-ci-cd.git'
            }
        }
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t demo-app .'
            }
        }
        stage('Run Container') {
            steps {
                sh 'docker run -d -p 8080:80 demo-app'
            }
        }
    }
}

