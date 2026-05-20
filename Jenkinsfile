pipeline {
    agent any

    tools {
        jdk 'Java 17'
        maven 'Maven_3.9'
    }

    stages {
        stage('Build') {
            steps {
                sh "mvn clean install -Dmaven.test.skip=true"
            }
        }
    }
}
