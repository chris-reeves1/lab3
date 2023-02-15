pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Make the script executable
                sh 'chmod +x build.sh'
                
                // Execute the script
                sh './build.sh'
            }
        }
    }
}


