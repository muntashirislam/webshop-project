pipeline {
    agent { docker { image 'node:10.8.0' } }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
                sh 'npm --version'
            }
        }
    }
}
