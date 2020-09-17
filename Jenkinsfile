pipeline {
    agent any
    tools {
        maven 'apache-maven-3.6.3'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -DskipTests clean package'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
