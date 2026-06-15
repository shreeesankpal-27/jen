pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat '"C:\\Users\\Sairaj\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" app.py'
            }
        }

        stage('Test') {
            steps {
                bat '"C:\\Users\\Sairaj\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" test.py'
            }
        }
    }
}