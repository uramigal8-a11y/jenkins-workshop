pipeline {
    agent any

    tools {
        terraform 'terraform-1.14.1'
    }

    stages {
        stage('Terraform Version') {
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
