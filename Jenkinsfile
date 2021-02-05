pipeline {
    agent { dockerfile true }
    stages {
        stage('test') {
            steps {
                sh 'node test.js'
            }
        }
    }
}