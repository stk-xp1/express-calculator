
       peline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                script {
                    checkout scm
                }
            }
        }
        
        stage('Build') {
            steps {
                script {
                    sh 'make build'
                }
            }
        }
        
        stage('Test') {
            steps {
                script {
                    sh 'make test'
                }
            }
        }
        
        stage('Deploy') {
            steps {
                script {
                    sh 'make deploy'
                }
            }
        }
    }
}
