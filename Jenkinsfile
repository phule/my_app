pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "/opt/apachemaven/bin/mvn clean"
            }
        }
        stage('--test--') {
            steps {
                sh "/opt/apachemaven/bin/mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "/opt/apachemaven/bin/mvn package"
            }
        }
    }
}
