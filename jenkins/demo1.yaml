pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'docker info'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'docker --version'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh 'docker images'
            }
        }
    }
}