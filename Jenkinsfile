/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'ruby:3.1.2-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'ruby --version'
                sh 'exit'
                sh 'cat /etc/os-release'
            }
        }
    }
}
