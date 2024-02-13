pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'This file used to create a new pipeline'
                sh 'echo Integrating Jenkins Pipeline with GitHub Webhook using Jenkinsfile'
            }
        }

        stage('test') {
            steps {
                echo 'This step testing some basic commands'
                sh 'whoami'
                sh 'pwd'
                sh 'ls'
            }
        }

        stage('run') {
            steps {
                echo 'These Python codes running version command and py file'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}
