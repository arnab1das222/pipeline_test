pipeline {
    agent any

    stages {
        stage('init') {
            steps {
                echo 'terraform init'
                terraform init
            }
        }
        stage('fmt') {
            steps {
                echo 'terraform fmt'
                terraform init
            }
        }
        stage('validate') {
            steps {
                echo 'terraform validate'
                terraform validate
            }
        }
        stage('plan') {
            steps {
                echo 'terraform plan'
                terraform plan
            }
        }
        stage('apply') {
            steps {
                echo 'terraform apply'
                terraform apply
            }
        }
    }
}