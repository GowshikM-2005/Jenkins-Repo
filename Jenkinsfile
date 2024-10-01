pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Insert your build commands here (e.g., mvn build, npm install)
                sh 'echo "Build process complete"'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Insert your testing commands here (e.g., unit tests, integration tests)
                sh 'echo "Tests are successful"'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Insert your deployment commands here
                sh 'echo "Deployment complete"'
            }
        }
    }

    post {
        always {
            echo 'This will always run after the stages, for cleanup or notifications.'
        }
        success {
            echo 'Pipeline succeeded!'
        }
       
    }
}
