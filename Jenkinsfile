pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('creating ECR Repository') {
            steps {
                echo 'creating ECR Repository'
                sh 'touch demo.txt'
            }
        }
        stage('building Docker Image') {
            steps {
                echo 'building Docker Image'
            }
        }
        stage('pushing Docker image to ECR Repository'){
            steps {
                echo 'pushing Docker image to ECR Repository'
            }
        }
        stage('creating infrastructure for the Application') {
            steps {
                echo 'creating infrastructure for the Application'
            }
         }
    }
}
