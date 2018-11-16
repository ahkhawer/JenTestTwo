pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'print hello'
            }
        }
        stage('deploy') {
            steps {
                sh 'echo hello'
            }
        }
    }
}
