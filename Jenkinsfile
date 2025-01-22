pipeline {
    agent any
    stages {
        stage('Install Dependencies') {
            steps {
                // bat 'npm install @playwright/test'
                bat 'npm install'
            }
        }
        stage('Run Playwright Tests') {
            steps {
                bat 'npx playwright install'
                bat 'npx playwright test'
            }
        }
    }
}