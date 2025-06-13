pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Jaideep-tech/webhook-demo-project.git'
            }
        }

        stage('Build') {
            steps {
                echo '✅ Build ho raha hai...'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deployment step chal raha hai...'
            }
        }
    }
}

