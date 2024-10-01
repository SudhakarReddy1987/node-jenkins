pipeline {
    agent any
    tools {
        nodejs 'NodeJS' // Name of the NodeJS installation from Global Tool Configuration
    }
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        // Add other stages as needed
    }
}
