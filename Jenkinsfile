pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Hello World from Build Stage!'
                echo 'Compiling source code...'
                echo 'Running unit tests...'
                echo 'Build completed successfully!'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Hello World from Deploy Stage!'
                echo 'Deploying to staging environment...'
                echo 'Deployment completed successfully!'
            }
        }
    }
    
    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
