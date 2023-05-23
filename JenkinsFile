pipeline {
    agent none

    stages {
        stage('Build') {
            agent {
                label 'build-agent' // Specify the label of the agent or use a custom label expression
            }
            steps {
                // Build steps here
            }
        }
        stage('Test') {
            agent {
                label 'test1-agent' // Specify the label of the agent or use a custom label expression
            }
            steps {
                // Test steps here
            }
        }
        stage('Deploy') {
            agent {
                label 'deploy-agent' // Specify the label of the agent or use a custom label expression
            }
            steps {
                // Deployment steps here
            }
        }
    }
}
