pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Running Build stage on branch: ${env.BRANCH_NAME}"
            }
        }
        stage('Test') {
            steps {
                echo "Running Test stage..."
                sh 'exit 1'
            }
        }
    }
}
