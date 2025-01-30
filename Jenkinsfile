pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo "Cloning repository..."
                git url: 'https://github.com/CanaEmma/partiel.git', credentialsId: 'github-credentials'
            }
        }
        stage('Build') {
            steps {
                echo "Hello, Jenkins! The build is running successfully."
            }
        }
    }
}
