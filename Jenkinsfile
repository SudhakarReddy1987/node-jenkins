pipeline {
    agent any
    tools {
        nodejs 'NodeJS' // This should match the name in Global Tool Configuration
    }
    stages {
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }
    }
}
