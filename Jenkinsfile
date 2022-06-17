node('docker') {
    stage('Build') {
        docker.image('php:8.1.0-alpine').inside {
            sh 'php --version'
        }
    }
}