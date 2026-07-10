pipeline {
    agent any

    stages {
        stage('Terraform Check') {
            steps {
                sh 'terraform version'
            }
        }
        stage('Terraform Init') {
            steps {
                sh 'terraform init'
            }
        }
    }
}
