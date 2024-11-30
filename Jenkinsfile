pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Example build command
                sh './build.sh'  // Replace with your actual build command
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Example test command
                sh './run-tests.sh'  // Replace with your actual test command
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Example deploy command
                sh './deploy.sh'  // Replace with your actual deploy command
            }
        }
    }
}
