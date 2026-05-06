pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Code pulled from GitHub'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing project'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment successful'
            }
        }
    }
}
