pipeline {
    agent { docker { image 'node:18.17.1-alpine3.18' } }
    stages {
        stage('pre-build') {
            steps {
                sh 'echo "pre-build stage"'
            }
        }
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
