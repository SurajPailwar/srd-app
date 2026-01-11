pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                echo 'Pulling code from GitHub'
                checkout scm
            }
        }

        stage('Basic Validation') {
            steps {
                echo 'Listing files'
                sh 'ls -l'
            }
        }
    }
}
