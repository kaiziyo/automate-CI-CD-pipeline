pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/kaiziyo/automate-CI-CD-pipeline.git'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t cicd-web-app .'
            }
        }

        stage('Deploy Application') {
            steps {
                sh '''
                docker stop web || true
                docker rm web || true
                docker run -d -p 80:80 --name web cicd-web-app
                '''
            }
        }
    }
}
