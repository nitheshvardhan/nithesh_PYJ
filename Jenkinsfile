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
                bat '"C:\Users\DanduNitheshVardhan\IdeaProjects\nithesh_PYJ\.venv\Scripts\python.exe" --version'
            }
        }
        stage('Run python'){
            steps {
                bat '"C:\Users\DanduNitheshVardhan\IdeaProjects\nithesh_PYJ\.venv\Scripts\python.exe "main.py'
            }
        }
    }
}