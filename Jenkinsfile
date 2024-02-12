pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "This file used to create a new pipeline"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
}
