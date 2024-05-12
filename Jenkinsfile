pipeline{
    agent any

    stages {
        stage('Build') {
            steps{
                //run maven on a unix agent
                bat "mvn clean package"
            }
        }
    }
}