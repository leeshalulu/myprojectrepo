pipeline {
    agent any
    
    stages {
        stage('Clone Repository') {
            steps {
                // Clone your repository
                git 'https://github.com/leeshalulu/myprojectrepo.git'
            }
        }
        
        stage('Build') {
            steps {
                // Commands for building your application
                echo 'Building the application...'
                // Example: sh 'make build' or other build commands
            }
        }
        
        stage('Test') {
            steps {
                // Commands for testing your application
                echo 'Testing the application...'
                // Example: sh 'make test'
            }
        }
        
        stage('Deploy') {
            steps {
                // Commands for deploying your application
                echo 'Deploying the application...'
                // Example: sh 'make deploy'
            }
        }
    }
}
