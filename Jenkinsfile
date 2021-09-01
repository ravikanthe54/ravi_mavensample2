pipeline{
    agent any
    stages{
        stage("maven test"){
            steps{
                sh "mvn test"

            }
        }
        stage("maven build"){
            steps{
                sh "mvn package"
            }
        }
    }
}