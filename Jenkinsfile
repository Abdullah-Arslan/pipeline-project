pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Welcome to Jenkins World'
                echo 'Dünyaya Hoş Geldin'
                sh 'python --version'
                sh 'linux --version'
                sh 'python pipeline.py'
            }
        }
    }
}
