pipeline {
agent any

```
stages {

    stage('Build') {
        steps {
            bat 'echo Building Application'
        }
    }

    stage('Test') {
        steps {
            bat 'echo Running Tests'
            bat 'echo All Tests Passed'
        }
    }
}

post {
    success {
        echo 'Build Successful'
    }

    failure {
        echo 'Build Failed'
    }
}
```

}
