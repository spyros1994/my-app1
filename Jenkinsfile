pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "/usr/share/maven/bin/mvn clean"
            }
        }
        stage('--test--') {
            steps {
                sh "/usr/share/maven/bin/mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "/usr/share/maven/bin/mvn package"
            }
        }
    }
}