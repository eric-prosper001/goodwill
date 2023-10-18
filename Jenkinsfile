pipeline{
    agent any
    stages{
        stage('Prosper Stage'){
            steps{
                sh'/var/lib/jenkins/workspace/goodwill/eptest.sh'
            }
        }
        stage('parallel'){
        parallel{
        stage('Erica Stage'){
            steps{
                sh'/var/lib/jenkins/workspace/goodwill/eptest.sh'
            }
        }
        stage('Bill Stage'){
            steps{
                sh'/var/lib/jenkins/workspace/goodwill/eptest.sh'
            }
        }
        }
        }
        stage('Jonas Stage'){
            steps{
                sh'/var/lib/jenkins/workspace/goodwill/eptest.sh'
            }
        }
    }
}