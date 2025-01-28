pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                echo 'Cloning the repository...'
                git url: 'https://github.com/CryingBaker/jenkins_pipeline.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Simulate build steps here
                echo 'Build step completed successfully.'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Simulate test steps here
                echo 'Test step completed successfully.'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // Simulate deploy steps here
                echo 'Deploy step completed successfully.'
            }
        }
    }
}
