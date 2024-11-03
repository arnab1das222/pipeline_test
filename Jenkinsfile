pipeline {
    agent any

    stages {
        stage('init') {
            steps {
                echo 'terraform init'
                script {
                    sh 'terraform init'
                }
            }
        }
        stage('fmt') {
            steps {
                echo 'terraform fmt'
                script {
                    sh 'terraform fmt'
                }
            }
        }
        stage('validate') {
            steps {
                echo 'terraform validate'
                script {
                    sh 'terraform validate'
                }
            }
        }
        stage('plan') {
            steps {
                echo 'terraform plan'
                script {
                    sh 'terraform plan'
                }
            }
        }
        stage('apply') {
            steps {
                echo 'terraform apply'
                script {
                    sh 'terraform apply'
                }
            }
        }
    }
}