pipeline{
    agent any
    stages{
        stage('Init'){
            steps{
                echo "Testing...."
            }
        }

        stage('Build'){
            steps{
                echo "Building...."
                sh "docker-compose up -f docker-compose-dev.yml -d"
            }
        }
        stage('Deploy'){
            steps{
                echo "code delyed...."
            }
        }
    }
}

