pipeline {
    agent { docker { image 'node:6.3' }}
    environment {
        PATH = "/usr/local/bin/docker:$PATH"
    }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}