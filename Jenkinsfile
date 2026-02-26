pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "Building project from Jenkinsfile..."
                bat "dir"
            }
        }

        stage('Create Artifact') {
            steps {
                bat "echo Build from Jenkinsfile > build.txt"
            }
        }
    }
}
