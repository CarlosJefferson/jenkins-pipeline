pipeline {
    agent none
    stages {
        stage('build') {
            agent { docker { image 'node:6.3' }}
            steps {
                sh 'npm --version'
            }
        }
    }
}