pipeline {
    agent {
        docker {
            label 'docker'
            image 'maven:3-alpine'
        }
    }

    stages {
        stage('Build') {
            steps {
                sh "mvn clean compile"
            }
        }
    }
}