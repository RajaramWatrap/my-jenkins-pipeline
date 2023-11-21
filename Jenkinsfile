pipeline {
    agent any
    stages {
        stage('Build and Test') {
            steps {
                sh 'chmod +x script.sh'
                sh './script.sh'
            }
        }
        stage('Deploy') {
            steps {
                // Add deployment steps here
                // For example:
                sh 'echo "Deploying..."'
            }
        }
    }
}
