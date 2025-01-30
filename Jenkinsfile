pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo "Cloning Repository..."
                git url: 'https://github.com/CanaEmma/partiel.git', credentialsId: 'github-credentials'
            }
        }
        stage('Build') {
            steps {
                echo "Hello, Jenkins! Build en cours..."
            }
        }
    }
}
