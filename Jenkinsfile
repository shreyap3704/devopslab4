pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/shreyap3704/devopslab4.git'
            }
        }

        stage('Build') {
            steps {
                echo "Build stage skipped (Static website)"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deployment placeholder"
            }
        }
    }
}
