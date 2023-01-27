pipeline {
    agent any
    stages {
        stage('Initialize'){
            steps{
                script{
                     echo "Initializing"
                }
            }
        }
        stage('git'){
            steps{
                script{
                    sh 'git checkout v1.0'
                }
            }
        }
    }
}