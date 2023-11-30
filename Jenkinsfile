pipeline {
    agent any

    stages {
        stage('Build TADS') {
            steps {
            bat'''
               docker info
               java --version
               docker compose version
               '''
            }
        }
    }
}