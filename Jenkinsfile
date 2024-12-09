pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                script{
                    bat 'docker build -t my-kube-app .'
                }
            }
        }
        stage('Test'){
            steps{
                script{
                    echo 'Running test...'
                }
            }
        }
        stage('Deploy'){
            steps{
                script{
                    echo 'Deploying application...'
                }
            }
        }
    }
}
