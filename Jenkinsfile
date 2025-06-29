// This is a simple Jenkins pipeline script for a generic project
pipeline {
    agent any // or agent { label 'ubuntu-agent' }

    stages {
        stage('Clone') {
            steps {
                sh 'echo "Cloning repository..."'
                // If using Git SCM in Jenkins config, this might not be needed
                // Replace with your actual git clone command
                //git 'https://your-git-repo-url.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building project..."'
                // Replace with your actual build command, e.g., mvn clean install
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
                // Replace with your actual test command, e.g., mvn test
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying application..."'
                // Replace with your actual deploy command
            }
        }
    }
}