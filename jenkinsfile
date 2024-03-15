pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add build commands here, e.g., 'mvn clean install'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands here, e.g., 'mvn test'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Add deployment commands here, e.g., 'kubectl apply -f deployment.yaml'
            }
        }
    }
    
    post {
        success {
            echo 'Pipeline executed successfully!'
            // Add any post-success actions here
        }
        failure {
            echo 'Pipeline execution failed!'
            // Add any post-failure actions here
        }
    }
}
