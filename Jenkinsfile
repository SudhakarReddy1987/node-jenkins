pipeline {
    agent any
    tools {
        nodejs 'nodejs' // This should match the name in Global Tool Configuration
    }
    stages {
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }
        stage('Check Node and npm Versions') {
            steps {
                sh 'node -v'
                sh 'npm -v'
            }
        }
    }
    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed. Please check the logs.'
        }
    }
}
