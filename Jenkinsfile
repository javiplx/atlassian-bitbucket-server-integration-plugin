pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                withMaven('maven': 'Maven_3.9.3') {
                    sh "mvn clean verify"
                }
            }
        }
    }
}
