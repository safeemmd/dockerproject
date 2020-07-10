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
                sh "docker-compose up -d"
            }
        }
        stage('Deploy'){
            steps{
                echo "code delyed...."
            }
        }
    }
}

