pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Mucahit from pipeline'
                sh 'echo integrating jenkins with Github using Jenkinsfile'
            }
        }
        stage('run') {
            steps {
                echo 'Reinvent yourself'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}