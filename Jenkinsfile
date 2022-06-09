pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Java Code'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running java code'
                sh 'java Hello'
            }
        }
    }
}