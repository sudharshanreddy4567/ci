pipeline{
    angent any
    stages{
        stages('Clone Repository'){
            steps{
                script{
                    
                }
            }
        }
        stages('Build and deploy'){
            steps{
                script{
                    sh 'echo "Building the applicatiom"
                    sh 'docker-compose down'
                    sh 'docker-compose build -d
                }
            }
        }
        post{
            always{
                echo 'pipeline is ecuction compltw.'
            }
        }
    }
}