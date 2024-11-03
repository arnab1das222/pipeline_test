pipeline {
    agent any

    stages {
        stage('init') {
            steps {
                echo 'terraform init'
                script {
                    terraform init
                }
            }
        }
        stage('fmt') {
            steps {
                echo 'terraform fmt'
                script {
                    terraform fmt
                }
            }
        }
        stage('validate') {
            steps {
                echo 'terraform validate'
                script {
                    terraform validate
                }
            }
        }
        stage('plan') {
            steps {
                echo 'terraform plan'
                script {
                   terraform plan
                }
            }
        }
        stage('apply') {
            steps {
                echo 'terraform apply'
                script {
                    terraform apply
                }
            }
        }
    }
}