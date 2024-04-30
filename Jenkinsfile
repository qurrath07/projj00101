pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building the Python code'
                sh 'main.py'
            }
        }
        // Other stages...
    }
    // Post-build actions...
}
