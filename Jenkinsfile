pipeline {
    agent any
    stages {
        
        stage('Deploy') {
            steps {
                // Use kubectl or helm to deploy your application to Kubernetes
                sh 'kubectl apply -f deployment.yaml -n yournamespace'
            }
        }
    }
}
