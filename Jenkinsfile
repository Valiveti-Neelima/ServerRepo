pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'mvn --version'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
