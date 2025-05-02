pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Anju062003/jenkins-demo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the code...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the code...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
