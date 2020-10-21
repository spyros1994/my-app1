pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "/usr/share/maven clean"
            }
        }
        stage('--test--') {
            steps {
                sh "/usr/share/maven test"
            }
        }
        stage('--package--') {
            steps {
                sh "/usr/share/maven package"
            }
        }
    }
}