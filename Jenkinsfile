pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/CryingBaker/jenkins_pipeline.git'
            }
        }
        stage('Build') {
            steps {
                sh './build-script.sh' // Replace with your build command
            }
        }
        stage('Test') {
            steps {
                sh './test-script.sh' // Replace with your test command
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to production...' // Add your deployment script
            }
        }
    }
}
