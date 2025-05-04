pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application using Docker Compose'
                sh 'docker-compose up -d'
            }
        }
    }
}
