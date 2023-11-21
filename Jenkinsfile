pipeline{

    agent any

    stages{

        stage('Run Test'){
            steps{
                sh "docker-sompose up"
            }
        }

        stage('Bring Grid Down'){
            steps{
                sh "docker-sompose down"
            }            
        }            

    }

}