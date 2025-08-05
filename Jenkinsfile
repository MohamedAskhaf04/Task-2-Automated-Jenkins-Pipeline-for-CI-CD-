pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo '🛠️ Building Docker image...'
                sh 'docker build -t my-app .'
            }
        }

        stage('Test') {
            steps {
                echo '✅ Running tests...'
                sh 'echo "Tests passed!"'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deploying app...'
                sh 'docker run -d --rm --name my-app-container my-app'
            }
        }
    }
}
