pipeline {
    agent { docker { image 'node:10.8.0' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
