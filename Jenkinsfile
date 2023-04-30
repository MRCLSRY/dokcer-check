pipeline {
    agent any
    stages {
        stage('Docker check') {
            steps {
                sh '''
                    docker info
                    docker version
                    docker-compose version
                    curl --version
                    jq --version
                '''
            }
        }
    }
}
