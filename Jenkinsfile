pipeline {
    agent any
    tools {
        nodejs 'NodeJS' // This should match the name in Global Tool Configuration
    }
    stages {
        stage('Check Node Version') {
            steps {
                sh 'node -v'
                sh 'npm -v'
            }
        }
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }
    }
}
