pipeline{
    agent any
    stages{
        stage('Prosper Stage'){
            steps{
                sh '/var/lib/jenkins/workspace/Bachanou/ajtest.sh'
            }
        }
        stage('parallel'){
        parallel{
        stage('Erica Stage'){
            steps{
                sh '/var/lib/jenkins/workspace/Bachanou/ajtest.sh'
            }
        }
        stage('Bill Stage'){
            steps{
                sh '/var/lib/jenkins/workspace/Bachanou/ajtest.sh'
            }
        }
        }
        }
        stage('Jonas Stage'){
            steps{
                sh '/var/lib/jenkins/workspace/Bachanou/ajtest.sh'
            }
        }
        stage('Gilbert Stage'){
            steps{
                sh '/var/lib/jenkins/workspace/Bachanou/ajtest.sh'
            }
        }
    }
}