pipeline {

    agent any

    stages {

        stage('Preparation SCM') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/josephc69/jenkins-stage-demo.git'
            }
        }
    
        stage('Build') {
            steps {
                echo 'Building the application'
            }
        }
    
        stage('Test') {
            steps {
                echo 'Testing the application'
            }
        stage('Deploy') {
            steps {
                echo 'Deploying the application'
            }
        }
    }
}