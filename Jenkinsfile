pipeline {
    agent any
    environment {
        PATH = "${env.PATH};C:\\Windows\\System32"
    }
    triggers {
        pollSCM('H/5 * * * *')  // Polls SCM every 5 minutes. Adjust as needed.
    }

    stages {
        stage('Build') {
            steps {
                script {
                    // Simulate a build step
                    echo 'Building...'
                    // You can add real build commands here
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    // Simulate a test step
                    echo 'Testing...'
                    // You can add real test commands here
                    // To simulate a failure, uncomment the next line
                    // error "Simulated failure"
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    // Simulate a deployment step
                    echo 'Deploying...'
                    // Add deployment commands here
                }
            }
        }
    }
}
