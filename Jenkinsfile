Jenkinsfile (Scripted Pipeline)
/* Requires the Docker Pipeline plugin */
node('docker') {
    stage('Build') {
        docker.image('php:8.1.0-alpine').inside {
            sh 'php --version'
        }
    }
}