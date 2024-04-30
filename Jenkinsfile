pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building the Python code'
                // No build steps required for this Python script
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the Python code'
                sh 'main.py'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the Python code'
                // No deployment steps required for this Python script
            }
        }
    }

    post {
        success {
            echo 'Pipeline successful'
            // Add any post-build actions here
        }
        failure {
            echo 'Pipeline failed'
            // Add any actions to take on failure here
        }
    }
}
