pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building HTML project...'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing HTML project...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying website...'
            }
        }
    }
}