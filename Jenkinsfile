pipeline{
    agent any
    stages{
        stage('Prosper Stage'){
            steps{
                sh 'Action1'
            }
        }
        stage('parallel'){
        parallel{
        stage('Erica Stage'){
            steps{
                sh 'df -h'
            }
        }
        stage('Bill Stage'){
            steps{
                sh 'lscpu'
            }
        }
        }
        }
        stage('Jonas Stage'){
            steps{
                sh 'ls'
            }
        }
        stage('Gilbert Stage'){
            steps{
                sh 'Action2'
            }
        }
    }
}