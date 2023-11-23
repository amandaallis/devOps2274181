pipeline {
    agent any

    stages {
        stage('Build TADS') {
            steps {
               docker info
               java --version
               docker compose version
            }
        }
    }
}