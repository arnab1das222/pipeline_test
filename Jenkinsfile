pipeline {
    agent any

    stages {
        stage('init') {
            steps {
                echo 'terraform init'
                sh 'terraform init'
            }
        }
        stage('fmt') {
            steps {
                echo 'terraform fmt'
                sh 'terraform init'
            }
        }
        stage('validate') {
            steps {
                echo 'terraform validate'
                sh 'terraform validate'
            }
        }
        stage('plan') {
            steps {
                echo 'terraform plan'
                sh 'terraform plan'
            }
        }
        stage('apply') {
            steps {
                echo 'terraform apply'
                sh 'terraform apply'
            }
        }
    }
}