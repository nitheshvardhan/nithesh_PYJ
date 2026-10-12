pipeline {
    agent any
    stages {
        stage('Checkout'){
            steps {
                checkout scm
            }
        }
        stage('Check python'){
            steps{
                bat 'python --version'
            }
        }
        stage('Run python'){
            steps {
                bat 'python main.py'
            }
        }
    }
}