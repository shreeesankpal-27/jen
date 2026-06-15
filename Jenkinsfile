pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building Application'
                bat 'python app.py'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Application'
                bat 'python test.py'
            }
        }
    }

    post {
        success {
            echo 'Build and Test Successful'
        }

        failure {
            echo 'Build Failed'
        }
    }
}