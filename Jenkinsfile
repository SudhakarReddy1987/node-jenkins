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
    }
}
