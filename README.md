pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Your build commands here (e.g., Maven, Gradle)
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Your test commands here (e.g., running unit tests)
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Your deploy commands here (e.g., deploying to a server)
            }
        }
    }
}
